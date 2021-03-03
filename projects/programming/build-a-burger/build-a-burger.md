# Build-A-Burger Application
{markdown: ./breadcrumb.md}

Creation Date: 2020/11/10

## Description
A training application used to development skills in micro-services
and the Angular framework.   

### Infrastructure Docker tools
- [ELK Stack Information](https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elastic-stack-on-centos-7) and ([ELK Stack Docker Image](https://hub.docker.com/r/devopsita85/elkstack-server-v6-8))
- [Artifactory Docker Image](https://hub.docker.com/r/pivotalservices/artifactory-resource)
- [ZipKin Trace Monitoring](https://hub.docker.com/search?q=Zipkin&type=image) 
- [Kabana](https://hub.docker.com/search?q=Kibana&type=image)
- [APM ~ Application Performance Monitoring](https://hub.docker.com/search?q=APM&type=image)
- [Jenkins](https://hub.docker.com/search?q=Jenkins&type=image)
- [Operational Visualization](https://hub.docker.com/search?q=Grafana&type=image)
- [Memcached](https://hub.docker.com/_/memcached)

### UI Requirements
* Install [NodeJs](https://nodejs.org/en/download/) for your development platform.
* Install [Angular/CLI](https://www.fosstechnix.com/how-to-install-angular-cli-on-windows-10/#:~:text=%20How%20to%20Install%20Angular%20CLI%20on%20Windows,update%20node.js%20and%20npm%20on%20windows...%20More%20). i.e. `npm install -g @angular/cli`
* Run `npm install`, i.e. (C:\Users\dqrom\projects\dqrapps\bab\bab-ui\bab-ui>) in the bab-ui to load up the node libraries.  

### Content Sites
* [Saveur](https://www.saveur.com/article/Techniques/Building-the-Perfect-Burger/)

### Aspect Logging
Here is a class I use in the web module for logging Enter/Exit and Exception logs in a Spring environment. 
```
package com.stgconsulting.bab.buns.web.aop.logging;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.ProceedingJoinPoint;
import org.aspectj.lang.annotation.AfterThrowing;
import org.aspectj.lang.annotation.Around;
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Pointcut;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.core.env.Environment;
import org.springframework.core.env.Profiles;
import org.springframework.stereotype.Component;

import java.util.Arrays;

/**
 * Aspect for logging execution of service and repository Spring components.
 *
 * By default, it only runs with the "local" and "dev" profile.
 */
@Aspect
@Component
public class LoggingAspect {

    private final Logger log = LoggerFactory.getLogger(this.getClass());

    private final Environment env;
    private Profiles profiles = Profiles.of("local", "dev");

    public LoggingAspect(Environment env) {
        this.env = env;
    }

    /**
     * Pointcut that matches all repositories, services and Web REST endpoints.
     */
    @Pointcut("within(@org.springframework.stereotype.Repository *)" +
            " || within(@org.springframework.stereotype.Service *)" +
            " || within(@org.springframework.web.bind.annotation.RestController *)")
    public void springBeanPointcut() {
        // Method is empty as this is just a Pointcut, the implementations are in the advices.
    }

    /**
     * Pointcut that matches all Spring beans in the application's main packages.
     */
    @Pointcut("within(com.stgconsulting.bab.buns.web.dao..*)" +
            " || within(com.stgconsulting.bab.buns.web.service..*)" +
            " || within(com.stgconsulting.bab.buns.web.controller..*)")
    public void applicationPackagePointcut() {
        // Method is empty as this is just a Pointcut, the implementations are in the advices.
    }

    /**
     * Advice that logs methods throwing exceptions.
     *
     * @param joinPoint join point for advice
     * @param e         exception
     */
    @AfterThrowing(pointcut = "applicationPackagePointcut() && springBeanPointcut()", throwing = "e")
    public void logAfterThrowing(JoinPoint joinPoint, Throwable e) {
        if (env.acceptsProfiles(profiles)) {
            log.error("Exception in {}.{}() with cause = \'{}\' and exception = \'{}\'", joinPoint.getSignature().getDeclaringTypeName(),
                    joinPoint.getSignature().getName(), e.getCause() != null ? e.getCause() : "NULL", e.getMessage(), e);

        } else {
            log.error("Exception in {}.{}() with cause = {}", joinPoint.getSignature().getDeclaringTypeName(),
                    joinPoint.getSignature().getName(), e.getCause() != null ? e.getCause() : "NULL");
        }
    }

    /**
     * Advice that logs when a method is entered and exited.
     *
     * @param joinPoint join point for advice
     * @return result
     * @throws Throwable throws IllegalArgumentException
     */
    @Around("applicationPackagePointcut() && springBeanPointcut()")
    public Object logAround(ProceedingJoinPoint joinPoint) throws Throwable {
        if (log.isDebugEnabled()) {
            log.debug("Enter: {}.{}() with argument[s] = {}", joinPoint.getSignature().getDeclaringTypeName(),
                    joinPoint.getSignature().getName(), Arrays.toString(joinPoint.getArgs()));
        }
        try {
            Object result = joinPoint.proceed();
            if (log.isDebugEnabled()) {
                log.debug("Exit: {}.{}() with result = {}", joinPoint.getSignature().getDeclaringTypeName(),
                        joinPoint.getSignature().getName(), truncate(String.valueOf(result)));
            }
            return result;
        } catch (IllegalArgumentException e) {
            log.error("Illegal argument: {} in {}.{}()", Arrays.toString(joinPoint.getArgs()),
                    joinPoint.getSignature().getDeclaringTypeName(), joinPoint.getSignature().getName());

            throw e;
        }
    }

    private String truncate(String results) {
        int maxLength = 50;
        if (results != null && !results.isEmpty()) {
            if (results.length() > maxLength) {
               return results.substring(0, maxLength).concat("...[truncated]");
            }
        }
        return results;
    }
}
```

Here is a sample of what the logs look like:
```
2020-11-11 21:25:04.160 DEBUG 38328 --- [0.1-8001-exec-9] c.s.b.b.web.aop.logging.LoggingAspect    : Enter: com.stgconsulting.bab.buns.web.controller.Buns.findAll() with argument[s] = []
2020-11-11 21:25:04.161 DEBUG 38328 --- [0.1-8001-exec-9] c.s.b.b.web.aop.logging.LoggingAspect    : Enter: com.stgconsulting.bab.buns.web.service.BunService.findAll() with argument[s] = []
2020-11-11 21:25:04.161 DEBUG 38328 --- [0.1-8001-exec-9] c.s.b.b.web.aop.logging.LoggingAspect    : Enter: com.stgconsulting.bab.buns.web.dao.BunsDao.findAll() with argument[s] = []
2020-11-11 21:25:04.162 DEBUG 38328 --- [0.1-8001-exec-9] c.s.b.b.web.aop.logging.LoggingAspect    : Exit: com.stgconsulting.bab.buns.web.dao.BunsDao.findAll() with result = [Bun(id=1, name=Ciabatta Roll, description=The thi...[truncated]
2020-11-11 21:25:04.162 DEBUG 38328 --- [0.1-8001-exec-9] c.s.b.b.web.aop.logging.LoggingAspect    : Exit: com.stgconsulting.bab.buns.web.service.BunService.findAll() with result = [Bun(id=1, name=Ciabatta Roll, description=The thi...[truncated]
2020-11-11 21:25:04.163 DEBUG 38328 --- [0.1-8001-exec-9] c.s.b.b.web.aop.logging.LoggingAspect    : Exit: com.stgconsulting.bab.buns.web.controller.Buns.findAll() with result = [Bun(id=1, name=Ciabatta Roll, description=The thi...[truncated]
```

#### logback.xml used
```
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE configuration>

<configuration scan="true">
    <include resource="org/springframework/boot/logging/logback/base.xml"/>

    <property name="LOG_PATH" value="${logging.file.path}"></property>
    <!-- The FILE and ASYNC appenders are here as examples for a production configuration -->
    <!--
        <appender name="FILE" class="ch.qos.logback.core.rolling.RollingFileAppender">
            <rollingPolicy class="ch.qos.logback.core.rolling.TimeBasedRollingPolicy">
                <fileNamePattern>${LOG_PATH}/logFile.%d{yyyy-MM-dd}.log</fileNamePattern>
                <maxHistory>90</maxHistory>
            </rollingPolicy>
            <encoder>
                <charset>utf-8</charset>
                <Pattern>%d %-5level [%thread] %logger{0}: %msg%n</Pattern>
            </encoder>
        </appender>
        <appender name="ASYNC" class="ch.qos.logback.classic.AsyncAppender">
            <queueSize>512</queueSize>
            <appender-ref ref="FILE"/>
        </appender>
        <root level="${logging.level.root}">
            <appender-ref ref="ASYNC"/>
        </root>
    -->
    <appender name="STDOUT" class="ch.qos.logback.core.ConsoleAppender">
        <encoder>
            <charset>utf-8</charset>
            <pattern>%d %-5level [%thread] %logger{0}: %msg%n</pattern>
<!--            <pattern>%d{HH:mm:ss.SSS} [%thread] %-5level %logger{36} - %msg%n</pattern>-->
        </encoder>
    </appender>

    <logger name="com.sun" level="WARN"/>
    <logger name="org.apache" level="WARN"/>
    <logger name="org.apache.catalina.startup.DigesterFactory" level="OFF"/>
    <logger name="javax.management.remote" level="WARN"/>
    <logger name="javax.xml.bind" level="WARN"/>
    <logger name="ch.qos.logback" level="WARN"/>
    <logger name="springfox" level="WARN"/>
    <logger name="org.hibernate.validator" level="WARN"/>
    <logger name="org.hibernate" level="WARN"/>
    <logger name="org.hibernate.ejb.HibernatePersistence" level="OFF"/>
    <logger name="org.springframework" level="WARN"/>
    <logger name="org.springframework.web" level="WARN"/>
    <logger name="org.springframework.security" level="WARN"/>
    <logger name="org.springframework.cache" level="WARN"/>
    <logger name="org.springframework.boot" level="WARN"/>
    <logger name="org.springframework.cloud" level="WARN"/>
    <logger name="org.springframework.data" level="WARN"/>
    <logger name="com.netflix" level="WARN"/>
    <logger name="com.google" level="WARN"/>
    <logger name="com.sun.jersey" level="WARN"/>
    <!-- Local code base   -->
    <logger name="com.stgconsulting.bab.buns.web.controller" level="DEBUG"/>
    <logger name="com.stgconsulting.bab.buns.web.dao" level="DEBUG"/>
    <logger name="com.stgconsulting.bab.buns.web.service" level="DEBUG"/>

    <!-- https://logback.qos.ch/manual/configuration.html#shutdownHook and https://jira.qos.ch/browse/LOGBACK-1090 -->
    <shutdownHook class="ch.qos.logback.core.hook.DelayingShutdownHook"/>

    <contextListener class="ch.qos.logback.classic.jul.LevelChangePropagator">
        <resetJUL>true</resetJUL>
    </contextListener>

</configuration>
```

#### Source Repo (BitBucket)
- [build-a-burger](https://bitbucket.org/thegotobookteam/workspace/projects/BUIL)

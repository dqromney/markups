# Udemy - Spring Framework DevOps on AWS
{markdown: ./breadcrumb.md}

### Links

* [Spring Framework DevOps on AWS Course](https://www.udemy.com/spring-core-devops-on-aws/learn/v4/content) 
Steve Thomson - Look at the whole DevOps life cycle. Creating different environments for development.

##### Biography: John Thompson - Introduction
* Java - 10-15 years
* Pivital consultant
* Spring Framework Guru
* Loves Intellij

##### Messages - Lecture 2
* If you run into a issue; give him as much information as possible. Provide details. The more information provided the better he can help you.
* Please messaging system in the course if possible, otherwise email him. 
* Email: john@springframework.guru

##### Checking out of GitHub Repository - Lecture 3
* [GitHub for SpringFramework Guru Example](https://github.com/springframeworkguru/spring-mvc/tree/jpa-many-to-many)
* Generally speaking, the beginning and ending source code.
* Click on View Resources; click on Beginning.
* Example
    * mkdir <working-dir> && cd <working-dir>
    * git clone <repository clone>.git
    * Creates a directory of the downloaded repository
    * Change to <repository clone> directory
* Basically he stores his progressive projects in branches. 

##### Learning things about Spring and community - Lecture 4
* When you have problems, look at [Stack Overflow](http://stackoverflow.com). Some are actual developer commiters.
  
##### Lecture Property Hierarchy - Section 2 Lecture 14
* Good document regarding the [Spring Boot Property Hierarchy](docs.spring.io/spring-boot/docs/current/reference/html/boot-features-external-config.html) 
* A general rule is OS Environment takes precedence over local properties.

Spring Boot uses a very particular `PropertySource` order that is designed to allow sensible overriding of values, properties are considered in the following order:

1. Command line arguments.
2. Properties from `SPRING_APPLICATION_JSON` (inline JSON embedded in an environment variable or system property)
3. JNDI attributes from `java:comp/env`
4. Java System properties ( `System.getProperties()` )
5. OS environment variables
6. A `RandomValuePropertySource` that only has properties in random.*
7. Profile-specific application properties outside of your packaged jar (`application-{profile}.properties` and YAML variants).
8. Profile-specific application properties packaged inside your jar (`application-{profile}.properties` and YAML variants).
9. Application properties outside of you rpackaged jar (`application.properties` and YAML variants).
10. Application properties packaged inside your jar (`application.properties` and YAML variants).
11. @PropertySource annotations on your `@Configuration` classes.
12. Default properties (specified using `SpringApplication.setDefaultProperties`). 
   

     
    
    
    


   





  


# My Servers
{markdown: ./breadcrumb.md}

### Continuous Integration (CI)
These are applications used to build and deploy applications.
* [Jenkins Server (Ubuntu-64) (Docker)](http://ub64:8080/)
    * [Docker Image Detail](https://hub.docker.com/_/jenkins/)
    * Installation location: /home/dqromney/projects/docker/jenkins

### Database Servers

* [MySQL Server (Docker)](jdbc:mysql://ub4:3306) ~ jdbc:mysql://ubuntu-64.local:3306 root/
    * [Some commands](https://github.com/docker-library/mysql/issues/230) to make DB available to outside users.
    * (Docker shell) bash-4.2# mysql --user=root --password=somepassword
    *  mysql> SELECT User,authentication_string FROM mysql.user;
    *  mysql> GRANT USAGE ON *.* TO 'root'@'%'

### Source Repositories

These are applications used to store documentation and source code for applications.

* [BitBucket](https://bitbucket.org)
* [GitHub](https:/github.com)

### CI/CD
* [Jenkins (local)](http://ub64:8080/) [Jenkins (external)](http://jenkins.hopto.org)
* [Artifactory (local)](http://ub64:8081) [Artifactory (external)](http://artifactory.hopto.org)

### Other Servers
* [WD My Cloud EX2 Ultra](http://mycloudex2ultra/)
* [Network Gateway 192.168.1.1, 166.70.64.1](192.168.1.1)
* [Network DNS 192.168.1.1, 198.60.22.2, 198.60.22.22, 8.8.8.8](192.168.1.1)
* [Kafka Manager](http://ub64:9001) ub64:9001
* [Kafka Server](http://ub64:9003) http://ub64:9003
* [Zookeeper Server](http://ub64:2181) ub64:2181
* [Calibre Book Server (external)](http://books.hopto.org)
* [JellyFin Media Server (external)](http://jel.hopto.org)
* [Ubooquity E-Book Server (external)](http://ubooquity.hopto.org)


### Home Servers
| Name  | IP  | ssh  | uname -a  | Description  |
|:-:|:-:|:-:|:-:|:-:|
| Ubuntu 18.04.1 LTS | 192.168.1.100 | ub64 | Linux ub64 5.4.0-66-generic #74-Ubuntu SMP Wed Jan 27 22:54:38 UTC 2021 x86_64 x86_64 x86_64 GNU/Linux | 64-bit 16 GB with 2 TB onboard storage  |
| Raspberry Pi 2 | 192.168.1.102 | rpi2-2 | Linux rpi2-2 5.10.11-v7+ #1399 SMP Thu Jan 28 12:06:05 GMT 2021 armv7l GNU/Linux | 64-bit 2 GB  |
| Raspberry Pi 4 | 192.168.1.104 | rpi4-4 | Linux rpi4-4 5.10.11-v7l+ #1399 SMP Thu Jan 28 12:09:48 GMT 2021 armv7l GNU/Linux  | 64-bit 4 GB  |
| Raspberry Pi 4 | 192.168.1.105 | rpi4-8 | Linux rpi4-8 5.10.11-v7l+ #1399 SMP Thu Jan 28 12:09:48 GMT 2021 armv7l GNU/Linux  | 64-bit 8 GB  |
| Debian 9 | 192.168.1.108 | deb32  | Linux debian 4.9.0-14-686-pae #1 SMP Debian 4.9.246-2 (2020-12-17) i686 GNU/Linux | 32 bit 16 GB with 1 TB onboard storage  |
| MacMini 2013 | 192.168.1.110  | macmini  | Darwin Davids-MacMini.local 16.7.0 Darwin Kernel Version 16.7.0: Thu Jun 15 17:36:27 PDT 2017; root:xnu-3789.70.16~2/RELEASE_X86_64 x86_64 | i7 4GB, 1TB SSD Storage  |
| MacBook Pro (Retina, 15-inch, Mid 2014 | 192.168.1.112 | mbpro | Darwin DQR-2.local 18.7.0 Darwin Kernel Version 18.7.0: Tue Jan 12 22:04:47 PST 2021; root:xnu-4903.278.56~1/RELEASE_X86_64 x86_64 | 2.8 GHz Intel Core i7, 1TB SSD |

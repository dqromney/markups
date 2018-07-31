# My Servers
{markdown: ./breadcrumb.md}

### Continuous Integration (CI)

These are applications used to build and deploy applications.

* [Jenkins](http://192.168.0.45:8080)

### Source Repositories

These are applications used to store documentation and source code for applications.

* [BitBucket](https://bitbucket.org)
* [GitHub](https:/github.com)

### Home Servers
| Name  | IP  | ssh  | uname -a  | Description  |
|:-:|:-:|:-:|:-:|:-:|
| Ubuntu 18.04.1 LTS | 192.168.0.53 | ubunto-64.local | Linux ubuntu-64 4.15.0-29-generic #31-Ubuntu SMP Tue Jul 17 15:39:52 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux | 64-bit 16 GB with 2 TB onboard storage  |
| Raspberry Pi  | 192.168.0.53 ubuntu-64.local | raspi | Linux raspberrypi 4.9.59-v7+ #1047 SMP Sun Oct 29 12:19:23 GMT 2017 armv7l GNU/Linux  | 64-bit 2 GB with 5 TB store USB drive  |
| Debian 9 | 192.168.0.45 | debian32  | Linux debian 4.9.0-7-686-pae #1 SMP Debian 4.9.110-1 (2018-07-05) i686 GNU/Linux | 32 bit 16 GB with 1 TB onboard storage  |
| MacMini 2013 | 192.168.0.47 & 5  | macmini  | Darwin Davids-MacMini.local 16.7.0 Darwin Kernel Version 16.7.0: Thu Jun 15 17:36:27 PDT 2017; root:xnu-3789.70.16~2/RELEASE_X86_64 x86_64 | i7 4GB, 1TB storage  |
| Macbook Pro 2011 | 192.168.0.48 & 4 | macbookpro11 | Darwin DQR.local 17.4.0 Darwin Kernel Version 17.4.0: Sun Dec 17 09:19:54 PST 2017; root:xnu-4570.41.2~1/RELEASE_X86_64 x86_64 | i7 8 GB, 1TB SSD storage  |
| Macbook Pro 2013 | varies | macbookpro13 |  | TBD  |

### Database Servers

* [MySQL Server](jdbc:mysql://192.168.0.42:3306) ~ jdbc:mysql://192.168.0.42:3306 root/
* [MySQL Server (Docker)](jdbc:mysql://ubuntu-64.local:3306) ~ jdbc:mysql://ubuntu-64.local:3306 root/
    * [Some commands](https://github.com/docker-library/mysql/issues/230) to make DB available to outside users.
    * (Docker shell) bash-4.2# mysql --user=root --password=somepassword
    *  mysql> SELECT User,authentication_string FROM mysql.user;
    *  mysql> GRANT USAGE ON *.* TO 'root'@'%'

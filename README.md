# docker-ubuntu-nginx-php72
Docker config to create PHP 7.2, NGINX container

**Ubuntu 18.04  with NGINX (v1.14.0), PHP (v7.2.14), OPcache (v7.2.14) and Xdebug (v2.6.1)**


Ready to use docker container -> https://hub.docker.com/r/blackjack777/ubuntu-nginx-php72/

Ready to use docker env for development -> https://github.com/n0v3xx/docker-compose-ubuntu-nginx-php72

[![](https://images.microbadger.com/badges/image/blackjack777/ubuntu-nginx-php71:1.0.svg)](https://microbadger.com/images/blackjack777/ubuntu-nginx-php71:1.0 "Get your own image badge on microbadger.com")

[![](https://images.microbadger.com/badges/version/blackjack777/ubuntu-nginx-php71:1.0.svg)](https://microbadger.com/images/blackjack777/ubuntu-nginx-php71:1.0 "Get your own version badge on microbadger.com")

System Packages:
* git
* unzip
* vim
* nano
* libbz2-dev
* libicu-dev
* libmcrypt-dev
* libzip-dev
* libxml2-dev
* mysql-client
* supervisor
* nginx

PHP Packages:
* php7.2
* php7.2-fpm
* php7.2-common
* php7.2-curl
* php7.2-mbstring
* php7.2-xml
* php7.2-mysql
* php7.2-dev
* php7.2-bz2
* php7.2-intl
* php7.2-xdebug
* php7.2-ldap
* php7.2-memcached
* php7.2-soap
* php7.2-memcache
* php7.2-redis

Modify docker/ubuntu/php72/Dockerfile if you want more packages.

**Run**

    sudo docker run -t -i blackjack777/ubuntu-nginx-php72:1.0 /bin/bash
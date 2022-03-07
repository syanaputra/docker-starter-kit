# Docker Starter Kit - PHP 7.1 & MariaDB & phpmyadmin

A starter kit to run PHP 7.1, MariaDB, and phpmyadmin in docker environment

## Installing

Copy `.env.example` to `.env`

Modify what you need accordingly.

```
APP_NAME=shuttersdept
APP_PORT=8101
APP_DB_ADMIN_PORT=8102
DB_PORT=33016

MYSQL_ROOT_PASS=Hardc0re22
MYSQL_USER=root
MYSQL_PASS=Hardc0re22
MYSQL_DB=shuttersdept
```


## How to use

To start the server
```
docker-compose up -d
```

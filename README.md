# Symfony-docker

Is a repository for symfony using docker.

# Description

Docker for run Symfony 5 with docker-compose.

It is composed by 3 containers:

```
nginx -> web server
php -> PHP-FPM 7.4 version
mysql -> MySQL database
```

# Installation

```
docker-compose up -d --build
```

If all is correct you will see in your terminal:

```
Starting symfony-docker_nginx_1 ... done
Starting symfony-docker_php_1   ... done
Starting symfony-docker_mysql_1 ... done
```

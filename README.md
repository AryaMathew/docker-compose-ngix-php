# docker-compose-ngix-php
This is a sample website hosted - docker container with PHP-FPM and NGINX using docker-compose.

## Requirements
- [Install docker](https://docs.docker.com/engine/install/)
- [Install docker-compose](https://docs.docker.com/compose/install/)

## Prerequisite

1. A PHP application - website

2. The SSL certificate files inside the folder - certs.

```
git clone https://github.com/FujiClado/aws-elb-site.git  website
```

3. Custom nginx.conf file - nginx.conf



## Provisioning

1. Clone the repository
```
https://github.com/AryaMathew/docker-compose-ngix-php.git
```
2. Switch to the cloned directory
```
cd docker-compose-ngix-php
```
3. Start the docker containers using
```
docker-compose up -d
```
4. To stop and remove the containers,networks or volumes associated with this docker, you can use
```
docker-compose down -v
```

## Result

A docker container is created in nginx and php-fpm with SSL 

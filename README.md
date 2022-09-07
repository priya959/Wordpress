# Wordpress

## Introduction
WordPress is a hosted software-as-a-service (SaaS) platform that lets you build a website using WordPress building blocks.

# Getting Started-

## Installation using docker
## prerequisite:

Docker must be install on your machine.

Docker-compose also must be installed on your machine.

You can also check the installed versions by :
```bash
docker --version 
docker-compose --version
```

# Start the Service
## Two ways to run 
## 1 way by using github
## create a new directory wordpress :
```bash
cd Desktop 
mkdir wordpress
```

link - https://github.com/priya959/Wordpress/blob/master/docker-compose.yaml

you can download the docker-compose.yml file from above code. link.

```bash
docker-compose up
```
## Command for stop 
```bash
docker-compose down
```
## 2 way by using Docker Hub

Open a terminal 

```bash
docker pull priyanka0310/wordpress:1.0
docker run -p 8000:80 priyanka0310/wordpress:1.0
```
we can also verify the docker containers are up and running :
```bash
docker ps
```
open a browser write localhost:8000 for wordpress 
![wordpress!](https://github.com/priya959/Wordpress/blob/master/wordpress.png)
open a browser write localhost:8080 for phpadmin 
![wordpress!](https://github.com/priya959/Wordpress/blob/master/phpadmin.png)



# Wordpress

## Introduction
WordPress is a hosted software-as-a-service (SaaS) platform that lets you build a website using WordPress building blocks.

# Getting Started-

## Installation using docker
## prerequisite:

Docker must be install on your machine.
Docker-compose also must be installed on your machine.

You can also check the installed versions by :

docker --version 
docker-compose --version

## create a new directory wordpress :

cd Desktop 
mkdir wordpress

link - https://github.com/priya959/Wordpress/blob/master/docker-compose.yaml
you can download the docker-compose.yml file from above code. link.

## Start the Service

using docker-compose file:

docker-compose up 


we can also verify the docker containers are up and running :

docker ps
open a browser write localhost:8000 for wordpress 
![wordpress!](https://github.com/priya959/Wordpress/blob/master/wordpress.png)
open a browser write localhost:8080 for phpadmin 
![wordpress!](https://github.com/priya959/Wordpress/blob/master/phpadmin.png)



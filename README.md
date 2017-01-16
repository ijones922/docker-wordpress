# docker-wordpress
A lightweight docker environment for rapid quick themeing

## Whats Included
  - Wordpress
  - MySQL
  - phpmyadmin


## Setup

### Install Docker for Mac

[Download Here](https://docs.docker.com/docker-for-mac/)

### Clone Repo and Run Docker

`git clone git@github.com:ijones922/docker-wordpress.git`

Ensure docker is running and working
`docker -v`

Docker compose up
`docker-compose up --build`

Navigate to `localhost:8080` for wordpress

Navigate to `localhost:3030` for phpmyadmin

`/theme` is mounted within the container and this is where you develop your theme.

### Configuration

In the docker-compose.yml file you can edit the environment variables if needed.

username: root
mySQL DB name: wordpress
mySQL password: docker

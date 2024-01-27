# php-hello-world
A simple hello-world for composer

Installation
------------

Inbrowser Demo
--------------
![Site Demo](https://github.com/sairajbudhathoki/powerworkshop-DevOps/blob/main/images/inbrowser.png?raw=true)

Install Docker and Docker Compose
``` bash
sudo apt install docker
```
``` bash
sudo apt install docker.io
```
``` bash
install docker-compose
```

Install Composer and use Docker Compose
-------------

Install Composer
``` bash
composer Install
```

Run docker-compose.yml
``` bash
docker-compose up -d
```


Github Actions
------------
![Github Actions](https://github.com/sairajbudhathoki/powerworkshop-DevOps/blob/main/images/github_actions.png?raw=true)

Docker Hub
----------------
![DockerHub](https://github.com/sairajbudhathoki/powerworkshop-DevOps/blob/main/images/imagepush.png?raw=true)

Pushing Image to DockerHub
``` bash
docker login
```

``` bash
docker build -t your_username/repository_name:tag .
```

``` bash
docker push your_username/repository_name:tag
```

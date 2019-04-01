# DOCKER TRAINING

## PREREQUISITES

In order to follow this Docker training you will need the following tools installed.

##### GIT

https://git-scm.com/download/

##### DOCKER

https://docs.docker.com/docker-for-windows/install/

##### VS CODE (OPTIONAL)

https://code.visualstudio.com/Download/

## ITINERARY

### 1 - DOCKER CLI

##### EXPLAIN AND REVIEW
- docker search
- docker pull
- docker inspect
- docker logs
- docker ps < -a -q >
- docker images < -a -q >
- docker rm < -f >
- docker rmi < -f >
- docker exec < -i -t -d -e >
- docker run < -i -t -d -e -v -p | --rm --name >
- docker kill
- docker start < -i >
- docker stop
- docker build < -t -q >

### 2 - DOCKERFILE
##### EXPLAIN AND REVIEW
- FROM (AS)
- ENV
- ARG
- VOLUME
- EXPOSE
- WORKDIR
- RUN
- ADD
- COPY
- CMD
- ENTRYPOINT

### 3 - CLI EXERCICES

##### RUNNING INTERACTIVE DOCKER CONTAINER
docker run -it ubuntu /bin/bash

##### RUNING A WEBSERVER WITH EXPOSED PORTS
docker search httpd
docker pull centos/httpd
docker start -p 8080:80 -d --name web01 centos/httpd

### 4 - DOCKERFILE EXCERCICES

## SAMPLES AND EXERCICES

1 - [Create hello-world Dockerfile](/exercices/ex-1/)

2 - [Install and run a webserver](/exercices/ex-2/)

3 - [Make a POST docker image](/exercices/ex-3/)

4 - [Multi stage build with dotnet core](exercices/ex-4/)


## AUTHOR

Héctor López - [LinkedIn](https://www.linkedin.com/in/h%C3%A9ctor-l%C3%B3pez-rodr%C3%ADguez-3b6408b8/) | [Twitter](https://twitter.com/oktn1c3) | [GitHub](https://github.com/oktn)

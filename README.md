# Learning-Docker

## Docker Login

command to login to dockerhub

`docker login`

## Build image when the docker file is in the same directory that the executed command

`docker image build -t dockerhubid/reponame:tag  .`


## Docker push

`docker image push dockerhubid/repo:tag`


## Delete image

`docker image rm dockerhubid/repo:tag`


## Listing images


`docker image ls`


## Run docker

`docker container run -d --name name -p 8000:8080  dockerhubid/repo:tag`


## stop container

`docker container stop name`

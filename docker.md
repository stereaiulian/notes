# Containers

docker ps

docker start my_container

docker container ls

docker container rename CONTAINER NEW_NAME

docker kill my_container

docker rm /redis

docker top CONTAINER



# Images

docker images

docker image ls

docker image rm



# Save - Load
docker save IMAGE -o /path/to/file.tar  
or

docker save IMAGE > /path/to/file.tar

Ex:

docker save busybox -o busybox.tar  

___
docker load -i busybox.tar

# Export - Import

docker export CONTAINER > /path/to/file.tar

Or 

docker export -o /path/to/file.tar CONTAINER

In both cases, the CONTAINER parameter can be one of the following values:
The container name, either auto-generated or specified when the container started
The unique container hash assigned by the Docker engine
___

docker import /path/to/exampleimage.tgz





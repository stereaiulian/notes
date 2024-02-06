# Containers

docker ps

# Images

docker images

# Save - Export -Load
docker save IMAGE -o /path/to/file.tar  
or

docker save IMAGE > /path/to/file.tar

Ex:

docker save busybox -o busybox.tar  

___

docker export CONTAINER > /path/to/file.tar

Or 
docker export -o /path/to/file.tar CONTAINER

In both cases, the CONTAINER parameter can be one of the following values:
The container name, either auto-generated or specified when the container started
The unique container hash assigned by the Docker engine
___





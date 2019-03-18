# Run SophiaTX Node in Docker
Source code: [v1.1.0](https://github.com/SophiaTX/SophiaTX/releases/tag/1.1.0)

## Download
1. ```$ git clone https://github.com/jim380/sphtx_node```
## Build Image
2. ```$ docker build -t <image_name> .```
## Run Container
3. ```$ docker run --detach --name <image_name> <container_name>```
## Access Shell within Container
4. ```$ docker exec -it <container_name> bash```
## Start Node
5. ```$ ./sophiatxd```
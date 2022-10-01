# Docker Commands

### Build an image

- `.` indicates the directory in which docker file exist
- `-t <image_name>:<tag>` adding name to the image

`docker build .`

### Running a container

- `-d` dettached mode
- `-p` Port
- `-it` entering interactive mode
- `--rm` Remove ccontainer whenever container is stopped
- `--name <container_name>` adding name to the container

`docker run -p <client_port>:<exposed_port> <image_id>`

### List all docker process

`docker ps -a`

### Start a docker container

`docker start <container_id>`

### Stop a docker conatiner

`docker stop <container_id>`

### Fetches the logs printed by the container

`docker logs <container_id>`

### Removing container(s)

`docker rm <container(s)_id>`

### Lists all images

`docker images`

### Removing image(s)

`docker rmi <image(s)_id>`

### Copying from directory to Container or vice versa

`docker cp <src> <destionation>`

### Sharing an image

`docker tag <image_name> <docker_hub_image_name>`

`docker push <docker_hub_image_name>`

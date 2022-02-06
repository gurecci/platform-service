# docker-commands

List Running Docker Containers
### `docker ps`

Start a Container
### `docker start <container Id>`

Stop a Running Container
### `docker stop <container Id>`

Build an Image
### `docker build -t <docker user id>/<image name> .`

Run a Docker Image
### `docker run -p <external port>:<internal port> -d <docker user id>/<image name>`

Push an Image to Docker Hub
### `docker push <docker user id>/<image name>`

# Build Docker Image

Build a new docker image from this Dockerfile and assign the image a meaningful name, e.g. "my-jenkins:lts":

```
docker build -t my-jenkins:lts .
```

# Deploy Docker Image

Deploy the Image with Docker Compose

```
docker-compose up -d
```

# Access Docker Container

You can access your docker container (through a separate terminal/command prompt window) with a `docker exec` command such as:

```
docker exec -it my-jenkins bash
```

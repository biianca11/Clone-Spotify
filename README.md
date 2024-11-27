# Clone-Spotify


## DOCKER

### Images
```bash
# build image (from the same path where we have DockerFile)
docker build -t my-image-name .

#check images
docker images

# delete images
docker rmi image-id
```

### Containers
``` bash
# run container from image
docker run --name web-container -d -p 8080:80 web-image

# check container
docker ps -a

#delete container
docker rm web-container
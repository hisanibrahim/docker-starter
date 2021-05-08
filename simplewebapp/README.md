## Build docker image

`docker build . -t hisanibrahim/simplewebapp:latest`

## Create and start container from the image

`docker run -p 8080:8080 hisanibrahim/simplewebapp:latest`
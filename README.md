# Basic Commands

`docker version`

`docker run hello-world`

`docker run busybox echo hi there`

`docker ps --all`

`docker run redis`

`docker exec -it <ID> redis-cli`
    `docker exec -i -t <ID> redis-cli`
    `docker exec -i <ID> redis-cli`
    `docker exec -t <ID> redis-cli`

`docker run -it busybox sh`

`docker create busybox ping google.com`
    `docker start <ID>`
    `docker logs <ID>`
    `docker logs -f <ID>`
    `docker stop <ID>`
    `docker kill <ID>`

`docker system prune`

# Build

`docker build .`

`docker build . -t hisanibrahim/redis:latest`

# Manual Image Generation

`docker run -it alpine sh`
`docker commit -c 'CMD ["redis-server"]' <ID>`

# PORT forwarding

`docker run -p 8080:8080 hisanibrahim/simplewebapp:latest`
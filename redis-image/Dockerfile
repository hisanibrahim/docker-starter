# Use an existing docker as base
FROM alpine

# Download and install a dependency
RUN apk add --update redis

# Tell the image what to do when it starts
CMD ["redis-server"]
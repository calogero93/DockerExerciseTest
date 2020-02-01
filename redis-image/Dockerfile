# Use an existing docker image
FROM alpine


# Download and install dependecies
RUN apk add --update redis


# Tell the image what to do when it start as a container
CMD ["redis-server"]
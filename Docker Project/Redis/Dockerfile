# specify base image
FROM alpine

# create working directory 
WORKDIR /usr/app

#install redis in Alpine 
RUN apk add --update redis

# start the redis server
CMD ["redis-server"]
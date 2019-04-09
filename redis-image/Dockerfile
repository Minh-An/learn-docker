# Use existing image as base 
FROM alpine

# Download + install dependency 
RUN apk add --update redis
RUN apk add --update gcc

# Specify starting command for container
CMD [ "redis-server" ]

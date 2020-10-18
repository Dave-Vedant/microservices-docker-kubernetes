# Use an existing docker image as a base 
FROM alpine

## base image "alpine" specify -> 

# Downlaod and install a dependency
RUN apk add --update redis
RUN apk add --update gcc 



# Tell the image what to do when it starts as a container
CMD [ "redis-server" ]

## command line command ...
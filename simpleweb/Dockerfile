# base image specification 
FROM node:alpine

WORKDIR /usr/app      r
# specify support files and copy to container above container directory 
# improvement : for solve rebuild issue, we just copy package so no need to rebuild from scratch (by docker)
COPY ./package.json ./       
# Install some dependencies
RUN npm install
# Now, copy all the other files
COPY ./ ./

# Default command
CMD ["npm", "start"]
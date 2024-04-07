# specify base image
FROM node:18-alpine

# create working directory 
WORKDIR /usr/app

# copy package json into the container
COPY package.json ./

#install redis in Alpine 
RUN npm install

#Copy the other files 

COPY ./ ./

# start the app
CMD ["npm","start"]
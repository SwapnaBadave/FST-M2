# specify base image
FROM node:18-alpine

# create working directory 
WORKDIR /usr/app

# copy Package json file container
COPY package.json ./

#install redis in Alpine 
RUN npm install

# copy all other files into container
COPY ./ ./

# start the redis server
CMD ["npm","start"]
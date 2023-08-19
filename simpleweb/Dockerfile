#Specify a base image
FROM node:14-alpine
WORKDIR /usr/app

# install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# default cmd
CMD [ "npm", "start" ]
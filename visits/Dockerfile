# base
FROM node:alpine
WORKDIR '/usr/app'

#dependency
COPY package.json .
RUN npm install
COPY . .


#start
CMD [ "npm", "start" ]
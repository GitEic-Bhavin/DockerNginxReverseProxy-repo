FROM node:16-alpine

WORKDIR /server
COPY package.json .
RUN npm i   ## npm install
COPY . . 
CMD [ "npm", "start" ]
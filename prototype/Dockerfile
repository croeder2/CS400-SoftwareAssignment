FROM node:alpine

WORKDIR /server

COPY package.json /server

COPY . /server 

RUN npm install

RUN npm install --save-dev jest

RUN npm run test

CMD node server.js

EXPOSE 8000 8001 8002 8003

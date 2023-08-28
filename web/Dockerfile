FROM node:18-alpine

WORKDIR /server

COPY package.json .
RUN npm install 

COPY . .

RUN npm install
RUN npm install --global nodemon


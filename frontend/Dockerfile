﻿FROM node:latest

WORKDIR /frontend/app

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]

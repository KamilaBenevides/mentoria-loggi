FROM node:latest

WORKDIR /home/node

COPY ./package.json package.json
RUN npm install
COPY ./babel.config.js babel.config.js
COPY ./public public
COPY ./src src

COPY ./src/index.js index.js

ENTRYPOINT [ "npm", "run", "serve" ]
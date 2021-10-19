FROM node:latest

WORKDIR /home/node

COPY ./package.json package.json
RUN npm install
COPY ./babel.config.js babel.config.js
COPY ./public public
COPY ./src src

ENTRYPOINT [ "npm", "run", "serve" ]
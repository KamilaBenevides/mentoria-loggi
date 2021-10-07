FROM node:latest

WORKDIR /home/node

COPY ./package.json package.json
RUN npm install

COPY ./src/index.js index.js

ENTRYPOINT [ "node", "index.js" ]
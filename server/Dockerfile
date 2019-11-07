FROM node:12.13-alpine

WORKDIR '/usr/app'

COPY ./package*.json ./

RUN npm install

COPY ./ ./

CMD ["node", "index.js"]

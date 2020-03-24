FROM node:12.2.0-alpine as build

RUN mkdir -p /tmp/src/client

WORKDIR /tmp/src/client

COPY package*.json /tmp/src/client/

RUN npm install

COPY . /tmp/src/client/

EXPOSE 3000

CMD ["npm", "start"]
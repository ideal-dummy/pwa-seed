FROM node:12.2.0-alpine as build

RUN mkdir -p /tmp/src/server

WORKDIR /tmp/src/server

COPY package*.json /tmp/src/server/

RUN npm install

COPY . /tmp/src/server/

EXPOSE 9000

CMD ["npm", "run", "dev"]
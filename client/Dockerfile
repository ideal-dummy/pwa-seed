FROM node:12.2.0-alpine

RUN mkdir -p /client

WORKDIR /client

COPY package*.json /client/

RUN npm install

COPY . /client/

EXPOSE 3000

CMD ["npm", "start"]
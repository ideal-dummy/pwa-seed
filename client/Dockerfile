FROM node:12.2.0-alpine

RUN mkdir -p /client

WORKDIR /client

COPY package*.json /client/

RUN yarn

COPY . /client/

EXPOSE 3000

CMD ["yarn", "start"]
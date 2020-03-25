FROM node:12.2.0-alpine

RUN mkdir -p /server

WORKDIR /server

COPY package*.json /server/

RUN yarn

COPY . /server/

EXPOSE 9000

CMD ["yarn", "dev"]
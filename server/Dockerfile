FROM node:12.2.0-alpine

RUN mkdir -p /server

WORKDIR /server

COPY package*.json /server/

RUN npm install

COPY . /server/

EXPOSE 9000

CMD ["npm", "run", "dev"]
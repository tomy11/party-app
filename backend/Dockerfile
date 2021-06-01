FROM node:16-alpine

WORKDIR /usr/src/app/party

COPY ./package.json ./
COPY ./yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 5000

CMD [ "server.js" ]
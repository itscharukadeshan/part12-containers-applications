FROM node:16

WORKDIR /usr/src/app

COPY . .

RUN npm ci

ENV DEBUG=Express_Sever:*

CMD npm start

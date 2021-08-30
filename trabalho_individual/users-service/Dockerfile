FROM node:14-alpine

WORKDIR /users-service

COPY . .

RUN yarn

CMD yarn db:migrate && yarn watch

EXPOSE 7101
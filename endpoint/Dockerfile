FROM node:lts-alpine

COPY package.json yarn.lock /app/

WORKDIR /app

RUN yarn

COPY . .

ENTRYPOINT [ "yarn", "start" ]
FROM node:21

LABEL name=dov-bear

WORKDIR /app

COPY . .

RUN npm ci

ENV APP_PORT=3000

EXPOSE ${APP_PORT}

ENTRYPOINT node main.js
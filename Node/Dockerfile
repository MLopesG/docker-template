FROM node:10

WORKDIR . /app

COPY package*.json ./

RUN npm install
RUN npm i -g @adonisjs/cli

COPY . .

EXPOSE 2025

ENV TZ America/Campo_Grande

CMD [ "npm", "start" ]
FROM node:14.5.0-alpine

WORKDIR /app

COPY package.json .

RUN npm install --registry "https://registry.npm.taobao.org/"

COPY . .

EXPOSE 80

CMD [ "node", "app.js" ]
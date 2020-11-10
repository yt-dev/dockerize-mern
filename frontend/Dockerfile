FROM node:14.5.0-alpine

WORKDIR /app

COPY package.json .

RUN npm install --registry "https://registry.npm.taobao.org/"

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]
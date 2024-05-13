FROM node:alpine

RUN apk add --no-cache mongodb-tools

WORKDIR /backend

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5000

CMD [ "npm", "start" ]
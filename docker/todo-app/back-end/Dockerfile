FROM node:14-alpine

RUN apk add --no-cache nodejs npm

WORKDIR /app

COPY . /app

RUN npm install

RUN rm -rf /var/cache/apk/*

EXPOSE 3001

CMD [ "npm", "start" ]

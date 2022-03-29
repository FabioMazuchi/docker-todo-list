FROM node:14-alpine

RUN apk add --no-cache nodejs npm

RUN rm -vrf /var/cache/apk/*

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 3001

CMD [ "npm", "start" ]

FROM node:14-alpine

RUN apk add nodejs npm

RUN apk update

RUN apk add nodejs npm

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 3001

CMD [ "npm", "start" ]

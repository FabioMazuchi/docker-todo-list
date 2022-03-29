FROM node:14-alpine

# RUN apk add --no-cache nodejs npm

WORKDIR /app

COPY . ./

ADD node_modules.tar.gz ./

RUN npm install

COPY . ./
# RUN rm -rf /var/cache/apk/*

EXPOSE 3001

CMD [ "npm", "start" ]

FROM node:alpine
LABEL MAINTAINER="Ayman Mahmoud" INFO="Kubernetes Goat"

WORKDIR /usr/src/app

COPY code/package*.json ./

RUN npm install \
    && apk add --no-cache curl

COPY code/* ./

EXPOSE 3000

CMD [ "npm", "start" ]

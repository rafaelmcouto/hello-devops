FROM node:6-alpine

RUN apk add --update tini 

WORKDIR /usr/src/app

COPY . ${WORKDIR}

RUN npm install && npm cache clean --force

CMD /sbin/tini npm start
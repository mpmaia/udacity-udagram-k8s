FROM node:12

WORKDIR /opt/app

COPY www/ ./

RUN npm install

EXPOSE 8080

CMD [ "node", "server.js" ]

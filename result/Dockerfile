FROM node:12-alpine

WORKDIR /result
COPY . /result
RUN npm install

EXPOSE 80

CMD [ "node", "server.js" ]

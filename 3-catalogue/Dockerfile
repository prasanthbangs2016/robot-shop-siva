FROM node:14

EXPOSE 8080

WORKDIR /opt/apps

COPY package.json /opt/apps

RUN npm install

COPY server.js /opt/apps/

CMD ["node", "server.js"]
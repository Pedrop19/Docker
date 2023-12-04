FROM node:18.13.0
WORKDIR /etc/docker/nodejs/

COPY server.js /etc/docker/nodejs/server.js
RUN npm install

EXPOSE 3000
CMD ["node", "server.js"]

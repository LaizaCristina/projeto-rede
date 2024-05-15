FROM node:21
WORKDIR /back-node
COPY ./backend
EXPOSE 3000
RUN npm install
ENTRYPOINT node src/server.js
# CMD ["node", "src/server.js"]
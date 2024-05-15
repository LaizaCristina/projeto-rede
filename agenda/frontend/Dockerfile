FROM node:21
WORKDIR /front-node
COPY ./frontend
EXPOSE 3001
RUN npm install
ENTRYPOINT npm start
# CMD ["npm", "start"]
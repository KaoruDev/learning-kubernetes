FROM node:9.5.0-alpine
EXPOSE 3000
WORKDIR /app
ADD ./node_app/package.json .
RUN npm install
ADD ./node_app/index.js .
CMD npm start

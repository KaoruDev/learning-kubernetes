FROM node:9.5.0-alpine
EXPOSE 3000
WORKDIR /app
ADD ./package.json .
RUN npm install
ADD ./index.js .
CMD npm start

FROM node:7
WORKDIR /APP
COPY package.json /APP
RUN npm install
COPY . /APP
CMD node index.js
EXPOSE 8080

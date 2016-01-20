FROM node:latest

RUN mkdir /src

WORKDIR /src
ADD ./polden /src
RUN npm install
RUN npm install -g gulp
RUN gulp build

EXPOSE 3000

CMD node app.js
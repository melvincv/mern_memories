FROM node:16
WORKDIR /app

COPY package*.json .
RUN npm i \
    && npm i -g nodemon

COPY . .
EXPOSE 5000
CMD npm start


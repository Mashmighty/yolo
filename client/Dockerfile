FROM node:13.12.0-alpine

Run mkdir -p /app

WORKDIR /app

COPY package.json /app/
COPY package-lock.json /app/

RUN npm install

COPY . /app/

CMD [ "npm", "start" ]
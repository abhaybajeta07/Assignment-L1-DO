FROM node:18.12.1-buster-slim

WORKDIR /app

COPY package.json /app/package.json

COPY package-lock.json /app/package-lock.json

RUN npm install

COPY . .

CMD ["npm", "run", "start"]


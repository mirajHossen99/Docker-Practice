# Base Image
FROM node:latest


# Preparetion Commands / Settings

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000


# Startup Command

CMD [ "node", "index.js"]
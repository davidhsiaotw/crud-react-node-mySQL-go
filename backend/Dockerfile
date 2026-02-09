FROM node:22 AS build
WORKDIR /backend
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 8800
CMD ["node", "index.js"]

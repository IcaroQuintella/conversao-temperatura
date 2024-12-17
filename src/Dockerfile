FROM node:22.7-alpine
WORKDIR /app
EXPOSE 8080
COPY package.json .
RUN npm install
COPY . .
CMD [ "node", "server.js" ]
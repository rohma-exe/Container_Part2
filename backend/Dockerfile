FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8888

CMD ["node", "server.js"]  # Replace with your actual entry point
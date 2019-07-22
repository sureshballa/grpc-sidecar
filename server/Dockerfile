FROM node:10
EXPOSE 50051
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . /app/
CMD ["node", "/app/server.js"]
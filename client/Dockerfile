FROM node:10
EXPOSE 3000
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . /app/
CMD ["node", "/app/client-express.js"]
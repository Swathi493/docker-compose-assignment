FROM node:stretch-slim
WORKDIR /node
COPY package.json .
RUN npm install
COPY . .
CMD ["node", "myserver.js"]
EXPOSE 3000
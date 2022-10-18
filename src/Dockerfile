FROM node
WORKDIR /curso-docker
COPY package*.json ./
RUN npm install
COPY . /curso-docker/
EXPOSE 8080
CMD ["node", "server.js"]
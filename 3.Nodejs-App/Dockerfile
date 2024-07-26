FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

#In the server.js app is listening to port 80
EXPOSE 80

CMD ["node", "server.js"]

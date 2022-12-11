FROM node:14

WORKDIR /src2

COPY package*.json ./

RUN npm install

COPY . . 

EXPOSE 3000

CMD [ "node", "app.js" ]
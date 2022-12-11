FROM node

WORKDIR /src2

COPY package.json . 
COPY package-lock.json .

RUN npm install

COPY . . 

EXPOSE 3000

CMD [ "node", "app.js" ]
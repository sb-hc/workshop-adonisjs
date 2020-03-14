FROM node:8

WORKDIR . /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080
EXPOSE 3333

CMD [ "npm", "start" ]

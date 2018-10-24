FROM node:latest
WORKDIR /todo/src/app
COPY package*.json ./

RUN npm install
COPY . .
EXPOSE 5050
CMD [ "npm", "run", "nodemon" ]
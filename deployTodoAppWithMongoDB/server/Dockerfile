FROM node:latest
WORKDIR /todo/src/app
COPY package*.json ./

RUN npm install
COPY . .
EXPOSE 7070
CMD [ "npm", "run", "nodemon" ]
FROM node:alpine

WORKDIR /frontend

EXPOSE 2000

COPY . .
RUN npm install

CMD [ "npm", "run", "dev" ]
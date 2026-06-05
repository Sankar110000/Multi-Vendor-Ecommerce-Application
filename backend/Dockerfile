FROM node
WORKDIR /backend

COPY package.json .
COPY . .

RUN npm install


EXPOSE 8000
CMD [ "npm", "run", "start:dev" ]
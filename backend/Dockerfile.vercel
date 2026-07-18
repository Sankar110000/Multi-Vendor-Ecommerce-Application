FROM node
WORKDIR /backend

COPY package.json .

RUN npm --force install

COPY . .

EXPOSE 8000
CMD [ "npm", "run", "start:dev" ]
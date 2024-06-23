FROM node:16-alpine

WORKDIR /app

COPY package.json yarn.lock ./

RUN npm install
RUN npm install http-errors

COPY . .

CMD ["npm", "start"]



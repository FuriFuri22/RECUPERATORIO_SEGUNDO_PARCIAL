FROM node:18-alpine

WORKDIR /servidor

COPY package*.json .

COPY . .

RUN npm install

EXPOSE 5000

CMD ["npm", "start"]
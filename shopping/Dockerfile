FROM node:14.17.1

WORKDIR /app/shopping

COPY package.json .

RUN npm i

COPY . .

EXPOSE 8003

CMD ["npm", "start"]
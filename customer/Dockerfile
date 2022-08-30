FROM node:14.17.1

WORKDIR /app/customer

COPY package.json .

RUN npm i

COPY . .

EXPOSE 8002

CMD ["npm", "start"]
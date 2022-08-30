FROM node:14.17.1

WORKDIR /app/products

COPY package.json .

RUN npm i

COPY . .

EXPOSE 8001

CMD ["npm", "start"]
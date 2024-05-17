FROM node:18-slim

WORKDIR /hot-reloading

COPY package.json .

RUN npm i

COPY . .

EXPOSE 3000

CMD ["npm","run","start-watch"]
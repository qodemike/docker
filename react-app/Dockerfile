
FROM node:21.7.3-alpine3.20

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 4173

CMD [ "npm", "run", "start" ]
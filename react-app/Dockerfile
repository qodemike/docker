
FROM node:21.7.3-alpine3.20

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

EXPOSE 8080

CMD [ "npm", "run", "preview" ]
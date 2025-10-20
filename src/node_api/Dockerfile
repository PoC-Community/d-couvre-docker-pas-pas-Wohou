FROM node:12-alpine

WORKDIR /src/node_api

COPY . .

ENV PORT=8080

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "start"]

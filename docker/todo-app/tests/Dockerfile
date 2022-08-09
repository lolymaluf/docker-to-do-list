FROM node:14-alpine AS todotests

WORKDIR /todo-app

ADD mjgargani/puppeteer:trybe1.0 .

COPY . .

ENTRYPOINT ["npm", "test"]

FROM node:14-alpine AS todofront

WORKDIR /todo-app

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm", "start"]
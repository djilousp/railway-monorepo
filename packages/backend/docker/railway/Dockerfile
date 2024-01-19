FROM node:18.16.1 as build


WORKDIR /app

### note, there is .dockerignore file in the project root which prevents `node_modules` from copying here
COPY . .
RUN npm ci

WORKDIR /app/packages/backend/ 


FROM node:14-alpine
WORKDIR /app
COPY package.json ./
ADD  node_modules.tar.gz ./
EXPOSE 3000
CMD [ "npm", "start" ]
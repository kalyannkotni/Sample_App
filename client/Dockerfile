FROM node:alpine
WORKDIR '/app'
COPY package.json .
RUN npm install -g npm@10.0.0
COPY . .
CMD [ "npm", "start" ]
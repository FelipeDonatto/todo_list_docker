
FROM node:14

WORKDIR /usr/src/app

COPY package*.json ./

ADD ./node_modules.tar.gz .

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
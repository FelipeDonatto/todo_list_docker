


FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/src/app

COPY package*.json ./

ADD ./node_modules.tar.gz .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "test"]
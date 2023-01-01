FROM node:18.12.1

COPY pakcage*.json ./

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm","start"]
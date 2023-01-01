FROM node:18.12.1

COPY pakcage*.json ./

COPY . .

RUN npm install

EXPOSE 3001

CMD ["npm","start"]
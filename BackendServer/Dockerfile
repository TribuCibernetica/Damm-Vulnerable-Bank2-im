FROM node:20.18.2

WORKDIR /home/node/dvba

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
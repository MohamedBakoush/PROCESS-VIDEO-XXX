FROM node:latest

WORKDIR /client

COPY package*.json ./

RUN npm install

COPY . .

RUN npx prisma generate

RUN npm run build  

EXPOSE 3000
CMD [ "npm", "run", "dev" ]
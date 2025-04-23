FROM node:18-slim

LABEL authors=" Inna Graur"

WORKDIR /my_app

COPY . .

RUN npm install --only=production

CMD ["npm", "start"]
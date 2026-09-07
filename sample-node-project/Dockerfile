

FROM node:24-alpine

WORKDIR /app/src/app

#copy dependencies only
COPY package*.json ./


#install dependencies,[O
RUN npm ci  --omit=dev

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]

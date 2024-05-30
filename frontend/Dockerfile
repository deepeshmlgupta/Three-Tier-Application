FROM node:21
WORKDIR /frontend

RUN npm i
COPY . .
COPY .env.sample .env.local

EXPOSE 3000

CMD ["npm","run","dev"]

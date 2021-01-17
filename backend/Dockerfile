FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3001

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=password

CMD ["npm","start"]
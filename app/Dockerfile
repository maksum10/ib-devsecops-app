FROM node:18.13-bullseye-slim

WORKDIR /app
COPY package*.json /app/
RUN npm ci
COPY . /app

EXPOSE 9999

CMD ["npm", "start"]

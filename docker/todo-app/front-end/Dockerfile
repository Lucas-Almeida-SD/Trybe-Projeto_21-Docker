FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
ENV todobackend=3001
ENTRYPOINT [ "npm", "start" ]
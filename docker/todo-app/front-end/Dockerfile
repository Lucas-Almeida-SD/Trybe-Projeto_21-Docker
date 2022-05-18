FROM node:14-alpine
WORKDIR /front
ADD node_modules.tar.gz ./
COPY . .
EXPOSE 3000
ENV REACT_APP_API_HOST=todoback
ENV REACT_APP_API_PORT=3001
ENTRYPOINT [ "npm", "start" ]
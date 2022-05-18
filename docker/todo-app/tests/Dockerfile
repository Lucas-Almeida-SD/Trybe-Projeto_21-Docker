FROM node:14-alpine
WORKDIR /tests
ADD node_modules.tar.gz ./
COPY . .
ENV FRONT_HOST=todofront
ENV FRONT_PORT=3000
ENTRYPOINT [ "npm", "test" ]

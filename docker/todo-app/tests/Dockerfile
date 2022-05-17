FROM node:14-alpine
WORKDIR /tests
ADD ./node_modules.tar.gz .
COPY . .
ENV todofrontend=3000
ENTRYPOINT [ "npm", "test" ]

FROM node:10.1.0-stretch

COPY . ./
RUN apt-get update
RUN npm install

ENTRYPOINT ["/usr/local/bin/node", "server"]

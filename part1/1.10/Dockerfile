FROM ubuntu:16.04
EXPOSE 5000

WORKDIR /1.10

COPY . .

RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
RUN npm install

CMD npm start

FROM ubuntu:16.04

WORKDIR /1.7

RUN apt-get update && apt-get install -y curl

COPY script.sh .

CMD ["./script.sh"]

FROM ubuntu:latest

RUN apt-get update && apt-get upgrade
RUN apt-get install -y git

COPY ./ping-pong-api /root

CMD /root/ping-pong-api

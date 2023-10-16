FROM ubuntu:latest

RUN apt-get update && apt-get upgrade
RUN apt-get install -y git

COPY ./ping-pong-listener /root

CMD /root/ping-pong-listener

FROM ubuntu:latest

COPY text.txt /text.txt

RUN apt-get update 

RUN apt-get install -y cowsay

CMD cat text.txt | /usr/games/cowsay

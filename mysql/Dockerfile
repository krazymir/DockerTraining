# Taking base image
FROM ubuntu:latest

RUN apt update
RUN apt-get install mysql-server -y

CMD [ "service", "mysql", "start" ]
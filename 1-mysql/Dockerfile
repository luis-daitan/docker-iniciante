FROM mysql:5.6

MAINTAINER Anselmo Pfeifer: 0.1

ENV DEBIAN_FRONTEND noninteractive

ENV MYSQL_ROOT_PASSWORD=knkA9n7YnzvrDLE
ENV MYSQL_DATABASE=cobranca
ENV MYSQL_USER=cobranca
ENV MYSQL_PASSWORD=C41ZBxAmSLhRZliF

ENV FILE=cobranca.sql
ADD $FILE /tmp/dump.sql

EXPOSE 3306
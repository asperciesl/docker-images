FROM mysql/mysql-server:latest

ENV MYSQL_ALLOW_EMPTY_PASSWORD="yes"
ENV MYSQL_DATABASE=docker
ENV MYSQL_ROOT_PASSWORD=docker
COPY setup.sql /docker-entrypoint-initdb.d/
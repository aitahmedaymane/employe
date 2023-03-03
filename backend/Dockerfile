FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=employees_db

COPY init.sql /docker-entrypoint-initdb.d/

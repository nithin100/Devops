FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD=admin
ENV MYSQL_DATABASE=authorizeschema
ENV MYSQL_USER=Student
ENV MYSQL_PASSWORD=Student

ADD app.sql /docker-entrypoint-initdb.d/


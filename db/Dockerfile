FROM mysql:5.7
ADD ./employees.sql /docker-entrypoint-initdb.d

ENV MYSQL_DATABASE=emp_details \
    MYSQL_ROOT_PASSWORD=

EXPOSE 3306

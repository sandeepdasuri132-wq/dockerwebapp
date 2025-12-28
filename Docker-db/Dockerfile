FROM mysql:8.0-oraclelinux8

ENV MYSQL_ROOT_PASSWORD="devopspassword"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

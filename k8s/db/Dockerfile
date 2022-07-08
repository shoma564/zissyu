FROM mariadb:latest

COPY ./init.sql /docker-entrypoint-initdb.d/
COPY ./my.cnf /etc/mariadb/conf.d/

VOLUME [ "/var/lib/mysql" ]

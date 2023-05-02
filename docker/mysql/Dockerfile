# Base image
FROM mysql:8

COPY conf.d/config-file.cnf /etc/mysql/my.cnf

RUN chown mysql:mysql /etc/mysql/my.cnf

RUN chmod 600 /etc/mysql/my.cnf
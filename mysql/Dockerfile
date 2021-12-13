FROM mysql:5.7
EXPOSE 3306
COPY ./my.cnf /etc/mysql/conf.d/my.cnf

COPY ./.env /.env
RUN ["/bin/bash", "-c", "source /.env"]

CMD ["mysqld"]
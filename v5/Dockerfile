FROM mysql:5.6
ENV WHICH="master" "MYSQL_ROOT_PASSWORD"="mysqlmM"
RUN echo 'hello' \
&& mkdir /datas 
WORKDIR /datas
Volume /datas
COPY ./ ./
EXPOSE 3336
CMD mysqld

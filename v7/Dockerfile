FROM mysql:5.6
ENV WHICH="master" "MYSQL_ROOT_PASSWORD"="mysqlmM"
RUN echo 'hello' \
&& mkdir /datas 
WORKDIR /datas
VOLUME /data
VOLUME /etc/mysql
COPY ./ ./
#RUN cp -r $WHICH/my.cnf /etc/mysql/my.cnf && rm -rf ./*
EXPOSE 3359

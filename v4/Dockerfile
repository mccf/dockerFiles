FROM mysql:5.6
ENV WHICH="master"
RUN echo 'hello' \
&& mkdir /datas 
WORKDIR /datas
Volume /datas
COPY ./ ./
RUN ls -R && cp -r $WHICH/my.cnf /etc/my.cnf
EXPOSE 3336
CMD bash

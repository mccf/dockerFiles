FROM mysql:5.6
ENV WHICH="master"
RUN echo 'hello' \
&& mkdir /datas 
WORKDIR /datas
Volume /datas
COPY master ./
COPY slave ./
# RUN cp -r $WHICH/my.cnf /etc/my.cnf
RUN ls -R
EXPOSE 3336
CMD bash


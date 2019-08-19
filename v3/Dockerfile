FROM mysql:5.6
ENV WHICH="master"
RUN echo 'hello' \
&& mkdir /datas 
WORKDIR /datas
Volume /datas
COPY master ./
COPY slave ./
EXPOSE 3336
CMD bash

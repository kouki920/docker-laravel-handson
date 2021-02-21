FROM mysql:5.7

ENV MYSQL_DATABASE=laravel_local \
  MYSQL_USER=kou920 \
  MYSQL_PASSWORD=namakoyu9798 \
  MYSQL_ROOT_PASSWORD=himitudayo4649 \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf

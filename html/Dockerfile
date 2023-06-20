FROM phpmyadmin/phpmyadmin:latest AS phpmyadmin
ENV PMA_HOST=mysql
ENV MYSQL_ROOT_PASSWORD=secret
COPY --from=phpmyadmin / /var/www/html

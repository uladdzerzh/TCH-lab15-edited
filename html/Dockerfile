FROM phpmyadmin/phpmyadmin:latest
ENV PMA_HOST=mysql
ENV MYSQL_ROOT_PASSWORD=secret
COPY --from=phpmyadmin/phpmyadmin /usr/src/phpmyadmin /var/www/html


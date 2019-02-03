FROM nevinsm/php-fpm:7.2

ENV PHP_VERSION 7.2

RUN sed -i 's|.*user=.*|user=youruser|g' /etc/php/${PHP_VERSION}/fpm/pool.d/www.conf && \
    sed -i 's|.*group=.*|group=yourgroup|g' /etc/php/${PHP_VERSION}/fpm/pool.d/www.conf

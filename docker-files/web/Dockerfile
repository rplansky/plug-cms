FROM php:7.0
MAINTAINER Ricardo Plansky <plansky.dev@gmail.com>

WORKDIR /var/www

RUN apt-get update && apt-get install -y \
    nginx

EXPOSE 80

CMD ["php", "-a"]

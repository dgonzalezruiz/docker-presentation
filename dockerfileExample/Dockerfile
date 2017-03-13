FROM gcr.io/stacksmith-images/minideb:jessie-r11
MAINTAINER randomDockerUser  hello@world.com

RUN install_packages nginx

ADD files.tar.gz /var/www/html/

ENV DEBUG=TRUE

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

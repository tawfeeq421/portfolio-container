FROM ubuntu:latest
LABEL "Auther"="Tawfeeq Ahmed"
LABEL "Project"="Portfoli-Website"
RUN apt update
RUN apt install apache2 git -y
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
WORKDIR /var/www/html
VOLUME /var/log/apache2
ADD tawfeeq.tar.gz /var/www/html

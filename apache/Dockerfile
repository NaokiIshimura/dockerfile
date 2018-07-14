FROM centos:latest
RUN yum -y install httpd

ADD static-html-directory /var/www/html

CMD ["/usr/sbin/httpd", "-DFOREGROUND"]

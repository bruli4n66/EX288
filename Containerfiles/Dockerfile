FROM quay.io/redhattraining/httpd-parent

RUN echo "Hellocontainer!" > /var/www/index.html
RUN rm -rf /run/httpd
RUN mkdir /run/httpd

LABEL version="1.0"
LABEL description="This is a container file"
LABEL Redhat Training training@redhat.com


CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]



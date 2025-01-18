FROM quay.io/redhattraining/httpd-parent

RUN mkdir -p /var/www/html && echo "Hellocontainer!" > /var/www/index.html && rm -rf /run/httpd && mkdir /run/httpd

LABEL version="1.0" description="This is a container file" mantainer="Redhat Training training@redhat.com"

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

# Use the httpd-parent image as base
FROM quay.io/brulian/python-311

USER root

RUN mkdir -p /var/www/html/
RUN chmod -R 777 /var/www/html
RUN touch /var/www/html/index.html
RUN echo "Hello Container madafacka!" > /var/www/html/index.html
RUN rm -rf /run/httpd
RUN mkdir /run/httpd

LABEL version="3.11"
LABEL description="Python ContainerFile"

USER 1001

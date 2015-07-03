FROM centos
MAINTAINER mehul.jani@gmail.com

ADD nginx.repo /etc/yum.repos.d/nginx.repo

RUN yum install -y nginx

RUN echo "daemon off;" >>/etc/nginx/nginx.conf

EXPOSE 80

CMD nginx

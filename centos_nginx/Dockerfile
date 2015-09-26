FROM centos
MAINTAINER mehul.jani@gmail.com
ADD nginx.repo /etc/yum.repos.d/nginx.repo
RUN yum -y install nginx
RUN echo "daemon off;" >>/etc/nginx/nginx.conf
EXPOSE 80
CMD nginx

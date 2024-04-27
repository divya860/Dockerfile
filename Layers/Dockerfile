FROM almalinux:8
RUN yum install nginx -y
RUN echo "welcome to Dockerfile" > /usr/share/nginx/html/hello.html
RUN yum install git -y \
     && yum install maven -y \
     && yum install gcc -y
CMD ["nginx", "-g", "daemon off;"]s
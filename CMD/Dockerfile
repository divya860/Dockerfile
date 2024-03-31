FROM almalinux:8
RUN yum install nginx -yum
RUN echo "welcome to Dockerfile" > /usr/share/nginx/hello.html
CMD ["nginx", "-g", "daemon off"]
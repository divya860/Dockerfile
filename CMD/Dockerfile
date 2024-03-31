FROM almalinux:8
RUN yum install nginx -y
RUN echo "welcome to Dockerfile" > /usr/share/nginx/hello.html
CMD ["nginx", "-g", "daemon off"]
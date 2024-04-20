FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "welcome to Dockerfile" > /usr/share/nginx/html/hello.html
ENTRYPOINT ["nginx", "-g", "daemon off;"]
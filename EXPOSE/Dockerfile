FROM almalinux:8
RUN yum install nginx -y
#EXPOSE is not adding any functionality , it is just for information
EXPOSE 80/tcp
CMD ["nginx", "-g", "daemon off;"]
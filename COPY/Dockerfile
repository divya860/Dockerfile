FROM nginx
#removing default html
RUN rm -rf /usr/share/nginx/html/index.html
#files should be vaialble in current directory where docker file exist
COPY  index.html /usr/share/nginx/html/index.html
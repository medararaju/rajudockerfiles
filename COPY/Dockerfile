FROM almalinux
RUN yum install nginx -y
RUN rm /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off"]



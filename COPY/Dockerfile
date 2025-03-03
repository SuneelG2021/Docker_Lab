FROM almalinux:8
RUM yum update -y
RUN yum install nginx -y
RUM rm -rf /usr/share/nginx/html/index.html
COPY website/  /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]
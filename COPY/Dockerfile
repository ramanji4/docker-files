FROM almalinux:9
RUN dnf install nginx -y
RUN ["nginx", "-g", "daemon off;"]
CMD rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
#this ONBUILD instruction triggers only, when any other user uses this image 
CMD ["nginx", "-g", "daemon off;"]
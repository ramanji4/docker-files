FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80 
CMD ["nginx", "-g", "daemon off;"]

#here exposing port no is belongs to image, means nginx is opening port no 80.
#we just informing the port no to users, we are not doing funtion to open port no. 80
#here the nignx default port no is 80, we can modify the port no of nginx in nginx configuration and then we can EXPOSE the port no to users.
#we are just informing to users that the nginx container is opening port no 80.
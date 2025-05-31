FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="Sivakumar Reddy" \
    duration="120Hrs"
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]

#ENV sets the environment variables and also key value pairs.
#ENV variables can reflect to Image and containers as well which created with the same image.
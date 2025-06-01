FROM almalinux:9
RUN useradd expense
USER expense
CMD ["sleep", "100"]

#For security purpose we should not run containers using root user.
#containers must be on normal user at normal runtime
#So atleast last instruction should be USER with normal user. Here the containers will run with normal user 
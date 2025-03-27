
#USER Instruction in Dockerfile
# The USER instruction in a Dockerfile specifies the user ID (UID) or username under which the container should run. 
# By default, Docker containers run as the root user, which can pose security risks.

FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]
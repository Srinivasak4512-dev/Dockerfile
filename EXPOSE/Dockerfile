
#The EXPOSE instruction in a Dockerfile is used to declare the ports that the container will listen on at runtime. 
#However, it does not publish the ports automatically—it just acts as documentation for users and tools like Docker Compose.

FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 8080
CMD ["nginx","-g","daemon off;"]
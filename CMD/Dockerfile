
#The CMD instruction in a Dockerfile is used to define the default command that a container runs when it starts. 
#Unlike RUN, which executes commands at build time, CMD runs at container startup.


FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]
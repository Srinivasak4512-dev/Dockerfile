
#The COPY instruction is used to copy files and directories from the host machine to the container. 
#It is similar to ADD but does not support extracting archives or downloading from URLs.

FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
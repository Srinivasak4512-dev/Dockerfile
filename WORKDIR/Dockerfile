#WORKDIR Instruction in Dockerfile
#The WORKDIR instruction sets the working directory for any subsequent RUN, CMD, ENTRYPOINT, COPY, and ADD instructions in a Dockerfile.

FROM almalinux:9
RUN mkdir /tmp/docker
WORKDIR /tmp/docker
RUN pwd
RUN echo "Hello" > hello.txt
CMD ["sleep","100"]
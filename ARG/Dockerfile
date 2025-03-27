#ARG Instruction in Dockerfile
# The ARG instruction defines build-time variables that you can pass during docker build. 
# Unlike ENV, ARG values are not available inside a running container—only during the build process.


FROM almalinux:9
ARG course="DevOps with AWS" \
    duration="120hrs"
RUN echo "Course: $course, duration: $duration"
CMD ["sleep","100"] 
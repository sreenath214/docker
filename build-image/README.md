Dockerfile contains a set of instructions used by docker to build a container image. 
Instructions are:

FROM : Base Image 
RUN  : Execute commands during build
COPY : Copy files from local machine (build context) into the image
ADD :  automatic extraction of compressed archeives and remote urls
WORKDIR : set working directiory
ENV : set environment variales
EXPOSE :  port usage 
CMD : default command when container starts
ENTRYPOINT : Main executable for the container

Best practices :
1. use minimal and trusted base images
2. Keep images updo date
3. Dont run containers as root
4. Never store secrets in images
5. use .dockerignore file 
6. scan images vulnerabilities 
7. Reduce linux capabilities
8. use read-only filesystems
9. limit resource usage
10.use multi-stage builds




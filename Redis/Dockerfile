# Use an existing docker image as a base
FROM centos
# Download and install
RUN yum update -y \
    && yum install -y redis
# Tell the image what to do when it starts
CMD ["redis-server"]

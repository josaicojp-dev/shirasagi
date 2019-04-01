FROM centos:7

WORKDIR /src

# install required packages
RUN yum update -y \
    && yum install -y curl \
    && curl https://raw.githubusercontent.com/shirasagi/shirasagi/master/bin/install.sh | SS_HOSTNAME=localhost bash -s
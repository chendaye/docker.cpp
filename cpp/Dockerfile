FROM bretzel12/jenkins
LABEL maintainer="Lengo<chendaye666@gmail.com>"

ENV TZ "Asia/Shanghai"
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN mkdir -p /var/wtu/cpp

# Upgrade
RUN apt-get update
RUN apt-get upgrade -y

# # Install build environment
RUN apt-get install -y build-essential make git clang g++

# CMD ["/bin/bash"]

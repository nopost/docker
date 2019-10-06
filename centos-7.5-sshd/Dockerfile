FROM jupincu/centos:7.5
MAINTAINER Nopost (nopost@qq.com)
COPY centos-7.5-sshd/container-files /
RUN cd /install && sh ./docker_build.sh
EXPOSE 22 
ENTRYPOINT ["/config/bootstrap.sh"]

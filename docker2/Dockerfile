FROM ubuntu
MAINTAINER fullinpe@qq.com
ADD sources.list /etc/apt/
RUN apt update
RUN apt -y upgrade
RUN apt install -y net-tools inetutils-ping nano openssh-server lrzsz
ADD sshd_config /etc/ssh/
RUN service ssh restart

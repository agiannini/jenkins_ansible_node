FROM ubuntu:bionic

RUN apt-get update
RUN apt-get -y install openssh-server
RUN service ssh start
RUN mkdir ~/.ssh
RUN touch ~/.ssh/authorized_keys
RUN chmod 744 authorized_keys
RUN echo "$YOUR_KEY" > ~/.ssh/authorized_keys

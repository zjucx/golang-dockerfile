#This is a comment
FROM ubuntu
MAINTAINER cx <zju.chx@gmial.com>
#RUN apt-get install python-software-properties

#sudo add-apt-repository ppa:gophers/go
#add source
RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe"> /etc/apt/sources.list
RUN apt-get update
# install git
RUN apt-get -y install git
# install golang
RUN apt-get -y install golang
#install redis
RUN wget http://download.redis.io/redis-stable.tar.gz
RUN tar xzf redis-stable.tar.gz
RUN cd redis-stable
RUN make

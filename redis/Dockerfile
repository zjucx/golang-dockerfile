#This is a comment
FROM ubuntu
MAINTAINER cx <zju.chx@gmial.com>
#install wget
RUN apt-get -y install wget
#install make
RUN apt-get -y install make
#install redis
RUN wget http://download.redis.io/redis-stable.tar.gz
RUN tar xzf redis-stable.tar.gz
RUN cd redis-stable
RUN make

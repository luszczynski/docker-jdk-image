FROM luszczynski/core

MAINTAINER Gustavo Luszczynski

RUN cd /opt && \
	curl -s -k -L -C - -b "oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u92-b14/jdk-8u92-linux-x64.tar.gz | tar xfz -

ENV JAVA_HOME /opt/jdk1.8.0_92
ENV PATH $PATH:$JAVA_HOME/bin

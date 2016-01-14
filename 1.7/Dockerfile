FROM luszczynski/core

MAINTAINER Gustavo Luszczynski

RUN cd /opt && \
	curl -s -k -L -C - -b "oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-linux-x64.tar.gz | tar xfz -

ENV JAVA_HOME /opt/jdk1.7.0_79
ENV PATH $PATH:$JAVA_HOME/bin
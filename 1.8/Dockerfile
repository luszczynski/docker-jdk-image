FROM luszczynski/core

MAINTAINER Gustavo Luszczynski <gluszczy@redhat.com>

RUN cd /opt && \
	curl -s -k -L -C - -b "oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u65-b17/jdk-8u65-linux-x64.tar.gz | tar xfz -

ENV JAVA_HOME /opt/jdk1.8.0_65
ENV PATH $PATH:$JAVA_HOME/bin
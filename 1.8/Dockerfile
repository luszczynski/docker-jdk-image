FROM luszczynski/core

MAINTAINER Gustavo Luszczynski

ENV JDK_VERSION=111
ENV BUILD_VERSION=b14

RUN cd /opt && \
	curl -s -k -L -C - -b "oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u${JDK_VERSION}-${BUILD_VERSION}/jdk-8u${JDK_VERSION}-linux-x64.tar.gz | tar xfz - && \
	rm -rf /opt/jdk-8u${JDK_VERSION}-linux-x64.tar.gz

ENV JAVA_HOME /opt/jdk1.8.0_${JDK_VERSION}
ENV PATH $PATH:$JAVA_HOME/bin

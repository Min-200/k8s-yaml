FROM jenkins/inbound-agent:4.3-4
RUN yum install -y java-1.8.0-openjdk maven curl git libtool-ltdl-devel && \ 
    yum clean all && \
    rm -rf /var/cache/yum/*

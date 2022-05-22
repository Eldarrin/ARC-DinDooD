FROM registry.access.redhat.com/ubi8/ubi:8.6-754
COPY yum.repos.d /etc/yum.repos.d/

ENV JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.332.b09-1.el8_5.x86_64

RUN microdnf -y install git-2.27.0-1.el8 \
    java-1.8.0-openjdk-devel-1.8.0.332.b09-1.el8_5 \
    libicu-60.3-2.el8_1 \
    nmap-ncat-2:7.70-6.el8 \
    zip-3.0-23.el8 \
    unzip-6.0-45.el8_4 \
    jq-1.5-12.el8 \
    tar-2:1.30-5.el8 \
    sudo-1.8.29-7.el8_4.1 \
    powershell-7.1.4-1.centos.8.x86_64 \
    procps-ng-3.3.15-6.el8 \
    make-1:4.2.1-10.el8 && \
    microdnf clean all
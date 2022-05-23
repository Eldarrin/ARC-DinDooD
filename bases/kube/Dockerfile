FROM eldarrin/base-main:LATESTTAG

COPY yum.repos.d /etc/yum.repos.d/

RUN microdnf -y install kubectl-1.21.1-0 && \
    microdnf clean all

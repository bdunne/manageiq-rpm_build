# FROM quay.io/centos/centos:stream9
FROM registry.fedoraproject.org/fedora:43

WORKDIR /work

RUN dnf -y install createrepo_c git mock && \
    dnf clean all && \
    rm -rf /var/cache/dnf

FROM quay.io/pypa/manylinux2014_x86_64 AS manylinux

COPY epel.repo /etc/yum.repos.d/epel.repo
     
RUN yum check-update && \
     yum -y install \
     clang-3.9.0

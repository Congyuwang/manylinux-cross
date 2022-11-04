FROM quay.io/pypa/manylinux2014_x86_64 AS manylinux

COPY epel.repo /etc/yum.repos.d/epel.repo
     
RUN yum check-update && \
     yum -y install centos-release-scl && \
     yum -y install llvm-toolset-7 && \
     echo "source scl_source enable llvm-toolset-7" >> ~/.bashrc

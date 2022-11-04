FROM quay.io/pypa/manylinux2014_x86_64 AS manylinux

RUN yum check-update && \
    yum -y install centos-release-scl && \
    yum -y install llvm-toolset-7 \
    scl enable llvm-toolset-7 bash

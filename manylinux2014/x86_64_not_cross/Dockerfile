FROM quay.io/pypa/manylinux2014_x86_64 AS manylinux

RUN yum check-update && \
    yum -y install \
    clang \
    llvm \
    llvm-libs

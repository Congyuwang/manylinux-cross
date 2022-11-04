FROM quay.io/pypa/manylinux2014_x86_64 AS manylinux

RUN yum check-update && \
    yum install \
    llvm-dev \
    libclang-dev \
    clang

FROM quay.io/pypa/manylinux2014_x86_64 AS manylinux

COPY epel.repo /etc/yum.repos.d/epel.repo
     
RUN yum check-update && \
    yum -y install \
    clang-3.9.0
     
RUN export PATH=/opt/llvm-3.9.0/bin:$PATH

ENV LIBCLANG_PATH=/opt/llvm-3.9.0/lib64

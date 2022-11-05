FROM quay.io/pypa/manylinux2014_x86_64
     
RUN yum check-update && \
    yum -y install centos-release-scl && \
    yum -y install llvm-toolset-7 && \
    yum -y install llvm-toolset-7-clang-devel
     
ENV CLANG_PATH=/opt/rh/llvm-toolset-7/root/bin/clang
ENV LIBCLANG_PATH=/opt/rh/llvm-toolset-7/root/lib64

FROM quay.io/pypa/manylinux2014_x86_64
     
RUN yum check-update && \
     yum -y install centos-release-scl && \
     yum -y install llvm-toolset-7
     
RUN export PATH=$PATH:/opt/rh/llvm-toolset-7/root/bin
ENV LIBCLANG_PATH=/opt/rh/llvm-toolset-7/root/lib64

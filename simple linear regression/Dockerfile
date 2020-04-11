# SWAMI KARUPPASWAMI THUNNAI

FROM centos:8

MAINTAINER VISWESWARAN NAGASIVAM

RUN yum makecache
RUN dnf group install "Development Tools" -y

WORKDIR /lsr

COPY . /lsr


RUN g++ --std=c++11 lsr.h lsr.cpp simple_linear_regression_example.cpp -o a.out

CMD ["./a.out"]


FROM ubuntu:22.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt update &&               \
    apt install -y              \
    git                         \
    make                        \
    vim                         \
    build-essential             \
    bison                       \
    flex                        \
    libssl-dev                  \
    gcc-arm-linux-gnueabi       \
    gcc-arm-linux-gnueabihf     \
    gcc-aarch64-linux-gnu       \
    python2                     \
    python3                     \
    python3-pip                 \
    uuid-dev                    \
    libncurses-dev              \
    iasl

CMD [ "/usr/bin/bash", "--login" ]

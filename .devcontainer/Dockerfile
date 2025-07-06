FROM ubuntu:22.04

RUN apt-get update && apt-get install -y \
    curl \
    git \
    man \
    sudo \
    build-essential \
    less \
    nano \
    tree \
    procps \
    net-tools \
    iputils-ping \
    && apt-get clean

# Set a basic working directory
WORKDIR /workspace

# Set default shell prompt for clarity
RUN echo "export PS1='\u@codespace:\w$ '" >> /etc/bash.bashrc

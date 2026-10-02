FROM debian:bookworm

RUN apt update && apt install -y \
    git \
    curl \
    wget \
    vim \
    nano \
    tmux \
    python3 \
    python3-pip \
    python3-venv \
    build-essential \
    net-tools \
    iputils-ping \
    dnsutils \
    nmap \
    tcpdump \
    less \
    unzip \
    zip \
 && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

CMD ["/bin/bash"]
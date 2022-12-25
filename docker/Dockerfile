FROM debian:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -o Dpkg::Options::="--force-confold" -y --no-install-recommends \
    wget gcc g++ git make cmake curl expect python python3 python3-dev python3-pip rsync sudo unzip wget zip less ssh jq zsh tmux locales vim dnsutils etcd zstd openjdk-11-jdk iputils-ping maven netcat redis-tools nodejs man socat tree
RUN curl https://bootstrap.pypa.io/pip/2.7/get-pip.py|python2
RUN python3 -m pip install ipython rdbtools python-lzf mycli

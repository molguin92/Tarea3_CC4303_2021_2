FROM ubuntu:20.04

RUN apt-get update && \
    apt-get install iperf3 net-tools bash zsh python3 \
    python3-pip python3-virtualenv traceroute iputils-ping\
    build-essential -y
RUN pip install -U pip "pyparsing<3" matplotlib numpy pandas seaborn scipy


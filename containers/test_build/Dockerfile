FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl sudo git python python-pip software-properties-common upstart

RUN git clone https://github.com/bryan-lunt/StarCluster.git
RUN python StarCluster/utils/scimage_16_04.py

CMD ["/bin/bash"]

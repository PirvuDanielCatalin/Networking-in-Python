FROM kalilinux/kali-linux-docker

MAINTAINER Pirvu Daniel-Catalin <danut_pirvu2008@yahoo.com>

USER root

RUN apt-get update
RUN apt-get install -y build-essential git net-tools arp-scan nmap rtpflood python python-pip
RUN pip install scapy

RUN apt-get install -y tcpdump

RUN useradd -u 1000 -m rtuser
USER root
WORKDIR /home/rtuser

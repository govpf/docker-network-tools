FROM govpf/debian:buster

RUN sed -i 's|deb.debian.org|archive.debian.org|g' /etc/apt/sources.list \
&& sed -i 's|security.debian.org|archive.debian.org|g' /etc/apt/sources.list \
&& sed -i '/stretch-updates/d' /etc/apt/sources.list
 
RUN apt update && apt install -y \
                        bash \
                        curl \
                        dnsutils \
                        netcat \
                        nmap \
                        python3 \
                        socat \
                        traceroute \
                        tcpdump \
                        vim \
                        wget

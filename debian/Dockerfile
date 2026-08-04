FROM govpf/debian:trixie

LABEL govpf.fromimage="govpf/debian:trixie"
LABEL govpf.category="utility"

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        bash \
        curl \
        dnsutils \
        netcat-openbsd \
        nmap \
        python3 \
        socat \
        traceroute \
        tcpdump \
        vim \
        wget \
    && rm -rf /var/lib/apt/lists/*
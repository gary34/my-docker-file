FROM ubuntu:18.04
COPY source.list /etc/apt/sources.list

RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install --no-install-recommends --no-install-suggests -y \
    ca-certificates vim iputils-ping netcat curl dnsutils wget net-tools lsof

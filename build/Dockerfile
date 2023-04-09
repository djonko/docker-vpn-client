FROM ghcr.io/wfg/openvpn-client:3.1

RUN apk add --no-cache \
    tzdata

COPY credentials.txt /data/vpn/credentials.txt
COPY config-vpn.ovpn /data/vpn/config-vpn.ovpn

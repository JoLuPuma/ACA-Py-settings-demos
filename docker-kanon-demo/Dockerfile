FROM ghcr.io/openwallet-foundation/acapy-agent:py3.13-1.5.0

USER root

ADD https://github.com/stedolan/jq/releases/download/jq-1.6/jq-linux64 ./jq
RUN chmod +x ./jq


USER $user

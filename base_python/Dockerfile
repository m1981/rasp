FROM resin/armhf-alpine:latest
ENTRYPOINT []

RUN apk add --no-cache \
        python \
        python-dev \
        gcc \
        libc-dev \
        make
RUN apk add --no-cache curl
RUN curl https://bootstrap.pypa.io/get-pip.py > get-pip.py
RUN python get-pip.py
RUN pip install rpi.gpio bottle
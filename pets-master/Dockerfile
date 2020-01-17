FROM ubuntu:18.04

RUN apt-get update && apt-get install -y \
  python-dev \
  python-pip \
  libssl-dev \
  libffi-dev

RUN pip install petlib pytest

VOLUME ["/src"]
WORKDIR /src
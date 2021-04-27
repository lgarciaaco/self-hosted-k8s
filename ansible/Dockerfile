FROM python:3.7.10-stretch

RUN pip install pip --upgrade
RUN pip install ansible

RUN apt-get update -y && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
        sshpass \
	vim

WORKDIR /work

ARG UBUNTU_TAG="kinetic"
FROM docker.io/ubuntu:${UBUNTU_TAG}

ENV LANG="en_US.UTF-8"
ENV PATH="/root/.local/bin:$PATH"

WORKDIR /root
RUN apt-get update --yes
RUN apt-get install --yes wget
RUN apt-get install --yes curl
RUN apt-get install --yes make
RUN apt-get install --yes graphviz
RUN apt-get install --yes python3
RUN apt-get install --yes inkscape
RUN curl -fsSL https://d2lang.com/install.sh | sh -s --

FROM mcr.microsoft.com/devcontainers/base:0-jammy

RUN apt-get install software-properties-common

RUN apt-add-repository ppa:fish-shell/release-3 \
  && apt update \
  && apt install fish \
  && apt-get update \
  && apt-get install fzf 
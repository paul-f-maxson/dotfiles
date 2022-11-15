FROM mcr.microsoft.com/devcontainers/base:0-jammy

RUN apt-get update \
  && apt-get --assume-yes upgrade \
  && apt-get --assume-yes install software-properties-common

RUN apt-add-repository ppa:fish-shell/release-3 \
  && apt-get --assume-yes update \
  && apt-get --assume-yes upgrade \
  && apt-get --assume-yes install fish fzf 
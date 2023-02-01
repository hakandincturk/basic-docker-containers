FROM --platform=linux/amd64 ubuntu:bionic

RUN apt-get update
RUN apt-get update && apt-get upgrade && apt-get install -y pkg-config build-essential libudev-dev
RUN apt-get -y install curl wget gnupg sudo nano
RUN apt-get update && apt-get install -y lsb-release && apt-get clean all
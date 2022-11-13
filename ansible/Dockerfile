FROM alpine:3.16

#
# devcontainer requirements
#
RUN apk add git libgcc libstdc++ musl 

#
# Ansible Dev requirements
#
RUN apk add build-base python3-dev py3-pip yamllint

RUN pip3 install ansible ansible-lint

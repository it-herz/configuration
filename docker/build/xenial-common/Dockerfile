FROM ubuntu:xenial
MAINTAINER Dmitrii Zolotov <dzolotov@herzen.spb.ru>
ENV ANSIBLE_REPO="https://github.com/edx/ansible"
ENV CONFIGURATION_REPO="https://github.com/it-herz/configuration.git"
ENV CONFIGURATION_VERSION="master"

ADD util/install/ansible-bootstrap.sh /tmp/ansible-bootstrap.sh
RUN chmod +x /tmp/ansible-bootstrap.sh
RUN /tmp/ansible-bootstrap.sh

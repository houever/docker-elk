FROM docker.elastic.co/kibana/kibana:6.4.2

LABEL maintainer="349514537@qq.com"

COPY ./config/kibana.yml /usr/share/kibana/config/kibana.yml

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER kibana

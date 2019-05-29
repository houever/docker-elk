FROM docker.elastic.co/logstash/logstash:6.4.2

LABEL maintainer="349514537@qq.com"
COPY ./config /usr/share/logstash/config
COPY ./pipeline /usr/share/logstash/pipeline

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER logstash
FROM docker.elastic.co/elasticsearch/elasticsearch:6.8.7

LABEL maintainer="349514537@qq.com"

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/conifg/elasticsearch.yml

RUN echo "Asia/Shanghai" > /etc/timezone
# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
# RUN elasticsearch-plugin install -y x-pack
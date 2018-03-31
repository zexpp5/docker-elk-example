FROM registry.cn-hangzhou.aliyuncs.com/hybit/logstash-6.2.3

COPY ./config /usr/share/logstash/config
COPY ./pipeline /usr/share/logstash/pipeline

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER logstash
FROM registry.cn-hangzhou.aliyuncs.com/hybit/kibana-6.2.3


COPY ./config/kibana.yml /usr/share/kibana/config/kibana.yml

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER kibana

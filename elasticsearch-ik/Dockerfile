
FROM docker.elastic.co/elasticsearch/elasticsearch:7.13.1
LABEL maintainer=kricsleo@163.com

RUN yum install -y wget && wget -c --tries=0 -O /tmp/elasticsearch-analysis-ik.zip https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.13.1/elasticsearch-analysis-ik-7.13.1.zip && \
    unzip /tmp/elasticsearch-analysis-ik.zip -d /usr/share/elasticsearch/plugins/ik && \
    rm -rf /tmp/elasticsearch-analysis-ik.zip
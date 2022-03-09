FROM docker.elastic.co/elasticsearch/elasticsearch:8.0.0

COPY ./plugins/* /tmp/plugins/

RUN unzip /tmp/plugins/ingest-attachment-8.0.0.zip -d /usr/share/elasticsearch/plugins/ingest-attachment
RUN unzip /tmp/plugins/elasticsearch-analysis-ik-8.0.0.zip -d /usr/share/elasticsearch/plugins/elasticsearch-analysis-ik


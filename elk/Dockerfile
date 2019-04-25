FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.4

RUN elasticsearch-plugin install ingest-geoip
RUN elasticsearch-plugin install ingest-user-agent

EXPOSE 9200 9300

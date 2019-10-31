FROM docker.elastic.co/elasticsearch/elasticsearch:6.4.3
RUN echo -e "prometheus.indices: false\nprometheus.cluster.settings: false" >> /usr/share/elasticsearch/config/elasticsearch.yml && /usr/share/elasticsearch/bin/elasticsearch-plugin install https://github.com/vvanholl/elasticsearch-prometheus-exporter/releases/download/6.4.3.0/prometheus-exporter-6.4.3.0.zip

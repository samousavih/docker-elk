# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.4.0

COPY ./logstash/pipline/logstash.conf /usr/share/logstash/pipeline
COPY ./logstash/config/logstash.yml /usr/share/logstash/config/logstash.yml

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

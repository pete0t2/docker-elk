# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.4.3

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-beats
RUN logstash-plugin install logstash-input-log4j
RUN logstash-plugin install logstash-filter-json
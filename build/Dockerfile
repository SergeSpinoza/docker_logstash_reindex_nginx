# https://github.com/elastic/logstash-docker
FROM logstash:6.6.0

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-geoip
RUN logstash-plugin install logstash-input-beats
RUN logstash-plugin install logstash-input-lumberjack
RUN logstash-plugin install logstash-patterns-core
RUN logstash-plugin install logstash-output-statsd

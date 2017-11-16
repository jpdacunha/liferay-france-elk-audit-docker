# https://github.com/elastic/logstash-docker
FROM logstash:2.4.1

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

RUN mkdir -p /usr/share/logstash/patterns \
    mkdir -p /usr/share/logstash/template \
    mkdir -p /usr/share/logstash/tomcat/logs

RUN logstash-plugin update logstash-input-beats
RUN logstash-plugin install logstash-filter-json



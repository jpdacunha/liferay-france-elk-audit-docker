
FROM elasticsearch:2.4.6

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

RUN /usr/share/elasticsearch/bin/plugin install analysis-icu
RUN /usr/share/elasticsearch/bin/plugin install analysis-kuromoji
RUN /usr/share/elasticsearch/bin/plugin install analysis-smartcn
RUN /usr/share/elasticsearch/bin/plugin install analysis-stempel


FROM kibana:4.6.5

# Add your kibana plugins setup here
# Example: RUN kibana plugin --install elastic/sense

#Remove before install avoid errors in case a new version of plugin exists
RUN kibana plugin --remove sense && kibana plugin --install elastic/sense
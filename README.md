# liferay-france-elk-audit-docker

This ELK Docker configuration allows to index Audit events from Liferay to Elasticsearch using logstash. It's can be used to simply start Liferay with ELK

1 - Copy the Liferay osgi configuration file in <LIFERAY_HOME>/osgi/configs (com.liferay.portal.security.audit.router.configuration.LoggingAuditMessageProcessorConfiguration.config)

2 - Change the path in the docker-compose with the path of your Liferay installation

3 - Configure Liferay to use the docker elasticSearch

4 - Start Liferay

5 - The Audit events like login are indexed in elasticsearch

NB : The index is not created automatically we still work on it :-)

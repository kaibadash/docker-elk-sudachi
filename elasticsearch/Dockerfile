ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

# Add your elasticsearch plugins setup here
RUN elasticsearch-plugin install analysis-kuromoji analysis-icu https://github.com/WorksApplications/elasticsearch-sudachi/releases/download/v3.0.0/analysis-sudachi-8.6.0-3.0.0.zip


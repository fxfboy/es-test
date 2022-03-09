# A repo for ElasticSearch and Kibana testing

- [Start ElasticSearch and Kibana in Docker](https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-stack-docker.html#run-docker-secure)

## .env
```
 # Password for the 'elastic' user (at least 6 characters)
  2 ELASTIC_PASSWORD=
  3 
  4 # Password for the 'kibana_system' user (at least 6 characters)
  5 KIBANA_PASSWORD=
  6 
  7 # Version of Elastic products
  8 STACK_VERSION=8.0.0
  9 
 10 # Set the cluster name
 11 CLUSTER_NAME=docker-cluster
 12 
 13 # Set to 'basic' or 'trial' to automatically start the 30-day trial
 14 LICENSE=basic
 15 #LICENSE=trial
 16 
 17 # Port to expose Elasticsearch HTTP API to the host
 18 ES_PORT=9200
 19 #ES_PORT=127.0.0.1:9200
 20 
 21 # Port to expose Kibana to the host
 22 KIBANA_PORT=5601
 23 #KIBANA_PORT=80
 24 
 25 # Increase or decrease based on the available host memory (in bytes)
 26 MEM_LIMIT=1073741824
 27 
 28 # Project namespace (defaults to the current folder name if not set)
 29 #COMPOSE_PROJECT_NAME=myproject
```

![arch](es-arch.png)

https://www.cnblogs.com/strongchenyu/p/13777596.html
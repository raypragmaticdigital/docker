
# Docker for ElasticSearch

Run the commands below. It will build both elasticsearch and kibana docker image, but you can also build at the same time.

Kibana is a source-available data visualization dashboard software for Elasticsearch

You can also copy the content of docker-compose.yml to your project.

## Build
Note that this will take time to build at first
```bash
>docker-compose build
>docker-compose up -d elasticsearch
>docker-compose up -d kibana
```

## Access ElasticSearch

This will display elasticsearch info once ready.

[http://localhost:9200](http://localhost:9200)

## Access Kibana

Once ready you can start to manage your elasticsearch data by accessing Menu -> Management -> Dev Tools

[http://localhost:5601](http://localhost:5601)

## Official PHP client for ElasticSearch
Connect your PHP webapp using the client below.

[elasticsearch-php](https://github.com/elastic/elasticsearch-php)
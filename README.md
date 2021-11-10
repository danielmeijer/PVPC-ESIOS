# Electricity

Obtain data from REE and saves it to elasticsearch in order to manage it locally.

## Usage 

```bash
cp .env.dist .env
```

Add your token to .env file.

```bash 
docker-compose up -d
```

You can get your data from elasticsearch deployed at ip:9200

## NOTICE

Elasticsearch and ElasticHQ is not securized and it hasn't any password, don't expose it!

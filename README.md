### Elasticsearch
---
https://www.elastic.co/jp/products/elasticsearch

https://github.com/elastic/elasticsearch

https://www.elastic.co/jp/

```sh
curl -XGET 'http://localhost:9200/twitter/_doc/1?pretty=true'
curl -XGET 'http://localhost:9200/twitter/_doc/2?pretty=true'
curl -XGET 'http://localhost:9200/twitter/_doc/3?pretty=true'

curl -XGET 'http://localhost:9200/twitter/_search?q=user:kimchy&pretty=true'
```

```yml
tread_pool:
  warmer:
    core: 1
    max: 8
    keep_alive: 2m
```


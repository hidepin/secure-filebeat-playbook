# secure-filebeat-playbook

## ElasticSearchのpipeline設定

``` shell
curl -XPUT 'http://xxx.xxx.xxx.xxx:9200/_ingest/pipeline/auth_pipeline' -d @auth_pipeline.json
```

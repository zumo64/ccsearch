# ccsearch

> Cross cluster Search Docker based Demo

### Overview
This is a small 3 clusters demo of the cross-cluster search feature
 - Cluster coord 1 node with cross-cluster search configured 
 - Cluster_one (1 node)
 - Cluster_two (1 node)
 - Kibana pointing to the coord node listening on localhost:5601

### Run
 - `docker-compose up`

### Test
 - Use postman or curl to ingest documents into cluster_one and cluster_two using respectively  http://localhost:9201 and http://localhost:9202 
 - send search requests in dev_tool.txt on the dev tool console of Kibana. 

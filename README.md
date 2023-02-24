# clickhouse-cluster

this repo contains docker compose setup for clickhouse cluster.

cluster setup: `remote_server.xml`
2 shards and each shard has 2 replicas.

docker compose services:
1. Zookeeper
2. Clickhouse servers
3. Clickhouse client (commented, i have client installed locally)

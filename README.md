# clickhouse-cluster

this repo contains docker setup for clickhouse database cluster.

cluster setup: `remote_server.xml`
2 shards and each shards have 2 replicas.

docker compose services:
1. Zookeeper
2. Clickhouse servers
3. Clickhouse client (commented, i have client installed locally)
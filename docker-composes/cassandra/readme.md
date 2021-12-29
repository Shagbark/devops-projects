## Docker commands for Cassandra

You can use these commands to work with Cassandra without docker-compose. 

### Start Cassandra

```bash
docker run --name cassandra-1 -p 9042:9042 -d cassandra:4.0.1
```
### Check status of node

```bash
docker exec cassandra-1 nodetool status
```

### Enter the cqlsh

```bash
docker exec -it cassandra-1 cqlsh
```
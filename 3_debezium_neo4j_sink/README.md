```sh
curl -X POST http://localhost:8083/connectors \
  -H 'Content-Type:application/json' \
  -H 'Accept:application/json' \
  -d @configs/datagen-users.json
```

```sh
curl -X POST http://localhost:8083/connectors \
  -H 'Content-Type:application/json' \
  -H 'Accept:application/json' \
  -d @configs/neo4j.sink.json
```

<!-- INSPIRATIONAL_QUOTE_START -->
> "The way to get started is to quit talking and begin doing." - Walt Disney
<!-- INSPIRATIONAL_QUOTE_END -->

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
The best way to predict the future is to create it.
🐯
<!-- INSPIRATIONAL_QUOTE_END -->

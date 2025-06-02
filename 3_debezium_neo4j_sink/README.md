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
![Image](https://github.com/user-attachments/assets/e5dd7943-9aef-4ee2-94a1-c411600f6674)
<!-- INSPIRATIONAL_QUOTE_END -->

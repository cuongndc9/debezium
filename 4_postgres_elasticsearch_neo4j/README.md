```sh
curl -X POST http://localhost:8083/connectors \
  -H 'Content-Type:application/json' \
  -H 'Accept:application/json' \
  -d @configs/source.json
```

```sh
curl -X POST http://localhost:8083/connectors \
  -H 'Content-Type:application/json' \
  -H 'Accept:application/json' \
  -d @configs/neo4j.sink.json
```

```sh
curl -X POST http://localhost:8083/connectors \
  -H 'Content-Type:application/json' \
  -H 'Accept:application/json' \
  -d @configs/es.sink.json
```

<!-- INSPIRATIONAL_QUOTE_START -->
![Image](https://github.com/user-attachments/assets/0e3d9ba0-f624-4a99-8a33-88703033a2a1)
<!-- INSPIRATIONAL_QUOTE_END -->

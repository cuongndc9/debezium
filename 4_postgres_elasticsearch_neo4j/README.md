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
> "A person who never made a mistake never tried anything new." - Albert Einstein
<!-- INSPIRATIONAL_QUOTE_END -->

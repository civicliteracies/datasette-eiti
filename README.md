## Requirements
- datasette v1.0a installed (https://docs.datasette.io/en/latest/installation.html)

## How to run locally

```
datasette eiti_database.sqlite --metadata metadata.yaml --config datasette.yaml --static static:static/ --template-dir=templates/
```

Datasette documentation: https://docs.datasette.io/en/latest/ 
# data-retention-mapper

Map data categories to retention and deletion requirements.

## Run

Requires Go 1.22+.

```sh
go run .
```

The tool reads its development gateway settings from `config/development.json`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.

## Model

This example targets the `gpt-6-astra` frontier model through the configured OpenAI-compatible router.

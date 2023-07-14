# elastic

# opentelemetry

Go to opentelemetry folder

```
export DT_API_TOKEN=<token>
export DT_OTLP_ENDPOINT=https://{your-env-id}.live.dynatrace.com/api/v2/otlp
export OTEL_EXPORTER_OTLP_METRICS_TEMPORALITY_PREFERENCE=delta

```
Deploy

```
docker compose up --no-build

```

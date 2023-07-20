# kubernetes deployment

Copy my-values-file.yaml 

```
helm install my-otel-demo open-telemetry/opentelemetry-demo --values my-values-file.yaml
```

# elastic

# opentelemetry

Clone this repo then go to opentelemetry folder

```
git clone https://github.com/vient28/elastic.git
cd elastic
cd opentelemetry
```

```
export DT_API_TOKEN=<token>
export DT_OTLP_ENDPOINT=https://{your-env-id}.live.dynatrace.com/api/v2/otlp
export OTEL_EXPORTER_OTLP_METRICS_TEMPORALITY_PREFERENCE=delta

```
Deploy

```
docker compose up --no-build

```
Check if running

```
docker ps | grep otel
```

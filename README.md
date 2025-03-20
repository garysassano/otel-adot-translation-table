# otel-adot-translation-table

This repository provides a mapping between OpenTelemetry (OTel) components and their corresponding AWS Distro for OpenTelemetry (ADOT) implementations.

## Component Mappings

| Component Type | OpenTelemetry (OTel) | AWS Distro for OpenTelemetry (ADOT) |
|---------------|----------------------|-------------------------------------|
| Collector (Core) | [opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) | [aws-otel-collector](https://github.com/aws-observability/aws-otel-collector) |
| Collector (Contrib) | [opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) | [aws-otel-collector](https://github.com/aws-observability/aws-otel-collector) |
| Lambda Extension | [opentelemetry-lambda](https://github.com/open-telemetry/opentelemetry-lambda) | [aws-otel-lambda](https://github.com/aws-observability/aws-otel-lambda) |
| Auto-Instrumentation (Node.js) | [opentelemetry-js-contrib](https://github.com/open-telemetry/opentelemetry-js-contrib/tree/main/metapackages/auto-instrumentations-node) | [aws-otel-js-instrumentation](https://github.com/aws-observability/aws-otel-js-instrumentation/tree/main/aws-distro-opentelemetry-node-autoinstrumentation) |
| Auto-Instruentation (Python) | [opentelemetry-python-contrib](https://github.com/open-telemetry/opentelemetry-python-contrib) | [aws-otel-python-instrumentation](https://github.com/aws-observability/aws-otel-python-instrumentation)

# otel-adot-translation-table

This repository provides a mapping between OpenTelemetry (OTel) components and their corresponding AWS Distro for OpenTelemetry (ADOT) implementations.

## Component Mappings

| Component Type | OpenTelemetry (OTel) | AWS Distro for OpenTelemetry (ADOT) |
|---------------|----------------------|-------------------------------------|
| Collector (Core) | [opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) | [aws-otel-collector](https://github.com/aws-observability/aws-otel-collector) |
| Collector (Contrib) | [opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) | [aws-otel-collector](https://github.com/aws-observability/aws-otel-collector) |
| Lambda Extension | [opentelemetry-lambda](https://github.com/open-telemetry/opentelemetry-lambda) | [aws-otel-lambda](https://github.com/aws-observability/aws-otel-lambda) |
| Node.js Auto-Instrumentation | [auto-instrumentations-node](https://github.com/open-telemetry/opentelemetry-js-contrib/tree/main/metapackages/auto-instrumentations-node) | [aws-distro-opentelemetry-node-autoinstrumentation](https://github.com/aws-observability/aws-otel-js-instrumentation/tree/main/aws-distro-opentelemetry-node-autoinstrumentation) |

## Purpose

This translation table helps developers understand the relationship between OpenTelemetry components and their AWS Distro for OpenTelemetry counterparts. ADOT is a secure, production-ready, AWS-supported distribution of the OpenTelemetry project that includes both core and contrib components.

# Structured Logs

## Definition

Structured logs are log records represented in a consistent machine-readable structure, commonly JSON, with explicit fields and values.

## 中文定义

结构化日志是以一致、机器可解析的结构记录的日志，常见形式为 JSON，并包含明确的字段和值。

## Why It Matters

Consistent fields make logs easier to query, aggregate, correlate, and analyze at scale.

## Example

A checkout service emits {"event":"payment_failed","order_id":"...","error_code":"card_declined"} rather than only a free-form sentence.

## Related Terms

- Telemetry
- Logging
- JSON
- KQL
- SQL

## Used In

- Observability
- Backend Engineering
- Data Engineering

## References

- OpenTelemetry logging guidance; standard structured-logging practice.

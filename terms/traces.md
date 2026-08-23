# Traces

## Definition

A distributed trace represents the end-to-end path of a request or operation through a distributed system. A trace is composed of one or more spans.

## 中文定义

链路追踪（Trace）表示一次请求或操作在分布式系统中的端到端路径；一条 Trace 由一个或多个 Span 组成。

## Why It Matters

Tracing helps identify where latency, failures, or dependencies arise across services.

## Example

A checkout trace shows time spent in the API, inventory service, payment provider, and database.

## Related Terms

- Span
- Telemetry
- Observability
- OpenTelemetry

## Used In

- Distributed Systems
- SRE
- Backend Engineering

## References

- OpenTelemetry documentation.

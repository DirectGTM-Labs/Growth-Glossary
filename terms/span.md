# Span

## Definition

A span is a single unit of work within a distributed trace, representing an operation with timing, attributes, and optional events or links.

## 中文定义

跨度（Span）是分布式链路追踪中的一个工作单元，表示某个具体操作，并通常包含时间信息、属性以及可选事件或关联。

## Why It Matters

Spans provide the fine-grained building blocks needed to understand a distributed trace.

## Example

A trace contains a span for an HTTP request and child spans for a database query and an external API call.

## Related Terms

- Traces
- Telemetry
- OpenTelemetry

## Used In

- Distributed Tracing
- Observability
- Backend Engineering

## References

- OpenTelemetry documentation.

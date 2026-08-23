# Transportation Layer

## Definition

The transportation layer of a data pipeline moves data reliably between producers and consumers, commonly using queues, brokers, or event-streaming systems.

## 中文定义

传输层是数据管道中负责在生产者与消费者之间可靠移动数据的层，常见实现包括消息队列、消息代理和事件流系统。

## Why It Matters

Separating transport from processing can provide buffering, retry, decoupling, and resilience when downstream systems are slower or temporarily unavailable.

## Example

A producer writes events to Kafka while multiple downstream consumers process the same event stream independently.

## Related Terms

- Message Queue
- Event Stream
- Kafka
- Data Pipeline
- Streaming Ingestion

## Used In

- Data Engineering
- Distributed Systems
- Event-Driven Architecture

## References

- Apache Kafka documentation; AWS messaging documentation; source document provided for this glossary.

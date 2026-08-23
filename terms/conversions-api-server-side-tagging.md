# Conversions API (CAPI) / Server-Side Tagging

## Definition

Conversions APIs and server-side tagging are server-mediated approaches for sending measurement or conversion events to analytics and advertising platforms rather than relying solely on browser-side tags.

## 中文定义

转化 API（CAPI）与服务端标记是通过服务器中介向分析或广告平台发送测量/转化事件的方法，而不是完全依赖浏览器端标签。

## Why It Matters

They can improve measurement resilience and data control in environments where browser-side signals are restricted or unreliable, while introducing additional implementation, consent, identity, and deduplication requirements.

## Example

A commerce backend sends a confirmed purchase event to an advertising platform after validating the order and applies the platform's required event identifiers.

## Related Terms

- Server-Side Tracking
- Event Deduplication
- Attribution
- Instrumentation

## Often Confused With

- Client-Side Tracking

## Used In

- MarTech
- Performance Marketing
- Analytics
- GTM

## References

- Meta Conversions API documentation; Google server-side tagging documentation; source document provided for this glossary.

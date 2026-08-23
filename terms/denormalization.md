# Denormalization

## Definition

Denormalization is the deliberate introduction of redundancy or precomputed structures into a data model to improve read performance, simplify analytical queries, or support a specific workload.

## 中文定义

反规范化是有意在数据模型中引入冗余或预计算结构，以改善读取性能、简化分析查询或服务于特定工作负载。

## Why It Matters

Analytical systems may trade some storage redundancy for simpler or faster queries.

## Example

A reporting table stores customer country directly with event facts to avoid repeated joins for a common dashboard.

## Related Terms

- Normalization
- Star Schema
- OLAP
- Materialized View

## Used In

- Data Warehousing
- Analytics
- Data Modeling

## References

- Kimball dimensional modeling literature; standard database practice.

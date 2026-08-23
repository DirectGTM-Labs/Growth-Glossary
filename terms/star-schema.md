# Star Schema

## Definition

A star schema is an analytical data model with a central fact table connected directly to dimension tables that describe the context of the facts.

## 中文定义

星型模式是一种分析型数据模型，由中心事实表和与其直接连接的维度表组成，维度表用于描述事实的上下文。

## Why It Matters

It provides a clear analytical structure that is often easy for BI tools and analysts to query.

## Example

A purchase fact table links directly to customer, product, date, and channel dimensions.

## Related Terms

- Fact Table
- Dimension Table
- OLAP
- Denormalization
- Snowflake Schema

## Used In

- Data Warehousing
- BI
- Analytics

## References

- Kimball dimensional modeling literature; source document provided for this glossary.

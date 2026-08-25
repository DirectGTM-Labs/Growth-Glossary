# Schema-on-read

## Definition

Schema-on-read defers imposing a rigid data schema until data is queried or interpreted rather than enforcing it at ingestion time.

## 中文定义

数据先像垃圾一样全扔进数据湖，直到我写代码去查询（Read）它的那一刻，才去解析它的结构格式。

## Why It Matters

Understanding Schema-on-read helps a growth practitioner make clearer decisions, define measurement correctly, and avoid confusing a useful tactic or implementation detail with a universal growth law.

## Example

For example, a growth team could incorporate Schema-on-read into an experiment, data pipeline, product system, or measurement workflow when the stated assumptions and implementation requirements are satisfied.

## Related Terms

- ETL
- Reverse ETL
- Snowflake Schema
- Parquet

## Used In

- Growth Engineering

## References

- Official technical documentation or relevant standards for the technology or protocol.
- Established engineering / data / analytics literature for methodological claims.

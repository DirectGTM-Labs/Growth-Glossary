# Normalization

## Definition

Normalization is a relational database design process that organizes attributes and relations to reduce inappropriate redundancy and update anomalies according to formal dependency rules.

## 中文定义

规范化是关系数据库设计过程，通过依据函数依赖等规则组织属性和关系，减少不当数据冗余及插入、更新、删除异常。

## Why It Matters

Normalization is especially useful for transactional systems where data integrity and consistent updates are priorities.

## Example

Customer attributes are stored in a customer relation rather than repeated independently across every transaction row.

## Related Terms

- Functional Dependencies
- OLTP
- Denormalization
- Third Normal Form

## Used In

- Database Design
- OLTP
- Data Modeling

## References

- Standard relational database theory; source document provided for this glossary.

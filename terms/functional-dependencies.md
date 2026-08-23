# Functional Dependencies

## Definition

A functional dependency X → Y states that, within a relation, a given value of X determines a single corresponding value of Y under the relation's stated semantics.

## 中文定义

函数依赖是数据库关系模型中的约束：X → Y 表示在给定关系语义下，X 的值能够唯一确定 Y 的值。

## Why It Matters

Functional dependencies help reason about keys, redundancy, and sound relational schema design.

## Example

If each customer_id uniquely identifies one customer email in a particular relation, customer_id → email is a functional dependency under that model.

## Related Terms

- Normalization
- Primary Key
- Candidate Key
- Relational Model

## Used In

- Database Design
- Data Modeling
- OLTP

## References

- Standard relational database theory; source document provided for this glossary.

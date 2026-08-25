# MurmurHash

## Definition

MurmurHash is a non-cryptographic hash family often used where fast, deterministic distribution of keys is useful, including stable experiment bucketing.

## 中文定义

一种非加密哈希算法，输入固定的 UserID，永远输出同一个分流桶号，确保用户刷新网页不会看到两个版本的“闪烁”。

## Why It Matters

Understanding MurmurHash helps a growth practitioner make clearer decisions, define measurement correctly, and avoid confusing a useful tactic or implementation detail with a universal growth law.

## Example

For example, a growth team could incorporate MurmurHash into an experiment, data pipeline, product system, or measurement workflow when the stated assumptions and implementation requirements are satisfied.

## Used In

- Growth Engineering

## References

- Official technical documentation or relevant standards for the technology or protocol.
- Established engineering / data / analytics literature for methodological claims.

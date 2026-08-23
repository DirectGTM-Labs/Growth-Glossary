# Sample Ratio Mismatch (SRM)

## Definition

Sample Ratio Mismatch is a statistically unlikely deviation between the observed allocation counts of experiment groups and the allocation ratio specified by the experiment design.

## 中文定义

样本比例失调（SRM）是实验实际观察到的各组样本数量与实验设计规定的分流比例之间出现统计上不太可能由随机波动解释的偏差。

## Why It Matters

SRM can indicate assignment, eligibility, logging, filtering, or data-pipeline problems and should be investigated before trusting experiment results.

## Example

An experiment designed for 50/50 allocation repeatedly produces a materially imbalanced assignment count, prompting an investigation of the assignment and logging pipeline.

## Related Terms

- A/A Test
- Randomization
- Chi-Square Test
- Experiment Integrity

## Used In

- A/B Testing
- Experiment Platform QA
- Analytics

## References

- Kohavi et al., Trustworthy Online Controlled Experiments; source document provided for this glossary.

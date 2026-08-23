# Experiment Triggering

## Definition

Experiment triggering is the rule that determines when an eligible user or unit is considered exposed to an experiment and therefore enters the analysis population for relevant outcomes.

## 中文定义

实验触发（Experiment Triggering）是定义实验对象何时被视为实际暴露于实验并因此进入相关结果分析总体的规则。

## Why It Matters

Correct triggering prevents users who never experienced the treatment from being incorrectly counted as exposed and helps align exposure with measurement.

## Example

A user is triggered only after the experiment variant has actually rendered, rather than merely after the page request begins.

## Related Terms

- Exposure
- Experiment Assignment
- Analysis Population
- Instrumentation

## Used In

- A/B Testing
- Experimentation
- Analytics

## References

- Kohavi et al., Trustworthy Online Controlled Experiments; source document provided for this glossary.

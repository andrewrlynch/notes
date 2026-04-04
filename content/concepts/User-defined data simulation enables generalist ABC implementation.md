---
cluster: false
created: '2026-03-31'
createdBy: fossick
elevated_at:
- 10
hub: true
hub_score: 10
members: []
modified: '2026-03-31'
order: 2
sources:
- '[@csillery_abc_2012]'
synthesis_status: draft
tags: []
title: User-defined data simulation enables generalist ABC implementation
type: concept
---

The generalist design of the [[concepts/approximate bayesian computation (abc)|abc]] package leaves [[concepts/data simulation|data simulation]] and summary statistic calculation to users rather than implementing problem-specific simulators. This approach provides flexibility to accommodate different [[concepts/complex models|complex models]] and allows the software to adapt to ongoing developments in ABC methodology. [@csillery_abc_2012]

## Definitions
- [[concepts/data simulation|data simulation]]
- [[concepts/summary statistics|summary statistics]]
- 
- [[concepts/complex models|complex models]]
- [[concepts/inference|inference]]
- [[concepts/models|models]]
- [[concepts/approximate bayesian computation (abc)|abc]]

## Synthesis
User-defined [[concepts/data simulation|data simulation]] is established as the foundational mechanism that allows generalist ABC packages to accommodate diverse statistical [[concepts/models|models]] without requiring explicit likelihood calculations, making approximate Bayesian computation accessible for [[concepts/complex models|complex models]] where traditional [[concepts/inference|inference]] is intractable. The mechanistic relationship operates through a deliberate architectural choice: by allowing users to specify their own data simulation functions, ABC frameworks can remain agnostic to model-specific details while still enabling [[concepts/parameter estimation|parameter estimation]] and [[concepts/model selection|model selection]] through comparison of [[concepts/summary statistics|summary statistics]] between observed and simulated data. This flexibility is essential because ABC analysis typically follows a trial-and-error approach requiring experimentation with different models and [[concepts/algorithms|algorithms]], which generalist packages must support within a single unified framework. While the core principle of simulation-based inference is well-established, the related concepts leave unresolved questions about how different choices of summary statistics and simulation designs affect the tradeoff between computational tractability and inferential precision across different classes of models.

## Related
- [[concepts/ABC enables model selection through comparison of observed and simulated data|ABC enables model selection through comparison of observed and simulated data]]
- [[concepts/Generalist ABC package accommodates flexible model and algorithm choice|Generalist ABC package accommodates flexible model and algorithm choice]]
- [[concepts/ABC bypasses likelihood evaluation through data simulation|ABC bypasses likelihood evaluation through data simulation]]

## Bibliography
- [[summaries/csillery-abc-2012|Abc: An R package for approximate Bayesian computation (ABC)]]
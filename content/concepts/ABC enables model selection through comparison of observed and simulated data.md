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
title: ABC enables model selection through comparison of observed and simulated data
type: concept
---

[[concepts/approximate bayesian computation (abc)|ABC]] performs [[concepts/model selection|model selection]] by using [[concepts/summary statistics|summary statistics]] derived from observed and simulated data rather than evaluating likelihood functions. This approach allows users to fit different [[concepts/models|models]] to their data and compare models within a Bayesian framework, which is integral to any [[concepts/bayesian analysis|Bayesian analysis]]. [@csillery_abc_2012]

## Definitions
- 
- [[concepts/model selection|model selection]]
- [[concepts/summary statistics|summary statistics]]
- [[concepts/likelihood function|likelihood function]]
- 
- [[concepts/bayesian analysis|bayesian analysis]]
- [[concepts/models|models]]
- [[concepts/approximate bayesian computation (abc)|ABC]]

## Synthesis
Approximate Bayesian computation enables [[concepts/model selection|model selection]] by generating simulated data from candidate [[concepts/models|models]] and comparing their [[concepts/summary statistics|summary statistics]] to those of observed data, thereby circumventing the need for analytically tractable likelihood functions. This simulation-based comparison allows researchers to evaluate which models best reproduce key features of real data through summary statistics that capture relevant information without requiring full likelihood calculations. The approach operates within a Bayesian framework where models are assessed based on how well their simulated outputs match observed patterns, making it particularly valuable for complex stochastic models where traditional likelihood-based model selection would be computationally prohibitive or impossible. However, the effectiveness of this model selection strategy depends critically on choosing appropriate summary statistics and [[concepts/algorithms|algorithms]], an area where generalist implementations provide flexibility but require users to navigate trial-and-error processes to optimize inferential precision against computational tractability.

## Related
- [[concepts/User-defined data simulation enables generalist ABC implementation|User-defined data simulation enables generalist ABC implementation]]
- [[concepts/Generalist ABC package accommodates flexible model and algorithm choice|Generalist ABC package accommodates flexible model and algorithm choice]]
- [[concepts/ABC bypasses likelihood evaluation through data simulation|ABC bypasses likelihood evaluation through data simulation]]

## Bibliography
- [[summaries/csillery-abc-2012|Abc: An R package for approximate Bayesian computation (ABC)]]
---
cluster: false
created: '2026-03-31'
createdBy: fossick
elevated_at:
- 13
hub: true
hub_score: 13
members: []
modified: '2026-03-31'
order: 2
sources:
- '[@csillery_abc_2012]'
synthesis_status: draft
tags: []
title: ABC bypasses likelihood evaluation through data simulation
type: concept
---

Approximate Bayesian computation ([[concepts/approximate bayesian computation (abc)|ABC]]) is a method that circumvents the computationally prohibitive evaluation of likelihood functions by comparing observed data with simulated data. Instead of calculating likelihoods directly, ABC uses [[concepts/summary statistics|summary statistics]] and simulations to enable [[concepts/inference|inference]] under [[concepts/complex models|complex models]] where exact likelihood calculations are infeasible. [@csillery_abc_2012]

## Definitions
- 
- [[concepts/likelihood function|likelihood function]]
- [[concepts/parameter estimation|parameter estimation]]
- [[concepts/summary statistics|summary statistics]]
- [[concepts/inference|inference]]
- [[concepts/complex models|complex models]]
- [[concepts/approximate bayesian computation (abc)|approximate bayesian computation (abc)]]
- [[concepts/data simulation|data simulation]]
- [[concepts/models|models]]

## Synthesis
Approximate Bayesian computation (ABC) is firmly established as a method that circumvents the need to calculate intractable or computationally prohibitive likelihood functions by instead generating simulated data from candidate [[concepts/models|models]] and comparing these simulations to observed data through [[concepts/summary statistics|summary statistics]]. The mechanistic relationship is clear: when [[concepts/complex models|complex models]] make direct likelihood evaluation infeasible, [[concepts/data simulation|data simulation]] becomes the core operation that enables Bayesian [[concepts/inference|inference]] to proceed, with summary statistics serving as the bridge between observed and simulated datasets to assess parameter plausibility and model fit. This simulation-based approach has been operationalized in generalist software packages that leave the specifics of data simulation to users, allowing flexibility across diverse applications while supporting various algorithmic refinements like [[concepts/nonlinear heteroscedastic regression|nonlinear heteroscedastic regression]] to improve [[concepts/parameter estimation|parameter estimation]] [[concepts/accuracy|accuracy]]. While the fundamental bypass mechanism is well-established, ongoing methodological developments suggest that optimal choices of summary statistics, tolerance thresholds, and regression adjustments remain active areas of refinement rather than settled questions.

## Related
- [[concepts/approximate bayesian computation (abc)|approximate bayesian computation (abc)]]
- [[concepts/User-defined data simulation enables generalist ABC implementation|User-defined data simulation enables generalist ABC implementation]]
- [[concepts/Nonlinear heteroscedastic regression improves ABC parameter estimation accuracy|Nonlinear heteroscedastic regression improves ABC parameter estimation accuracy]]
- [[concepts/ABC enables model selection through comparison of observed and simulated data|ABC enables model selection through comparison of observed and simulated data]]
- [[concepts/Generalist ABC package accommodates flexible model and algorithm choice|Generalist ABC package accommodates flexible model and algorithm choice]]

## Bibliography
- [[summaries/csillery-abc-2012|Abc: An R package for approximate Bayesian computation (ABC)]]
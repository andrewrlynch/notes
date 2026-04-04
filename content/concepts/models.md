---
cluster: false
created: '2026-03-31'
createdBy: fossick
elevated_at:
- 12
hub: true
hub_score: 12
members: []
modified: '2026-03-31'
order: 1
sources: []
synthesis_status: draft
tags: []
title: models
type: concept
---

## Definition
Mathematical or statistical representations of the relationships among variables in a system or process.

## Related Claims
- [[concepts/ABC bypasses likelihood evaluation through data simulation|ABC bypasses likelihood evaluation through data simulation]]
- [[concepts/ABC enables model selection through comparison of observed and simulated data|ABC enables model selection through comparison of observed and simulated data]]
- [[concepts/Generalist ABC package accommodates flexible model and algorithm choice|Generalist ABC package accommodates flexible model and algorithm choice]]
- [[concepts/User-defined data simulation enables generalist ABC implementation|User-defined data simulation enables generalist ABC implementation]]
- [[concepts/Aneuploidy exhibits dual roles as oncogenic and tumor-suppressive|Aneuploidy exhibits dual roles as oncogenic and tumor-suppressive]]
- [[concepts/Primary glioblastomas contain inherent variability in oncogenic signaling expression|Primary glioblastomas contain inherent variability in oncogenic signaling expression]]

## Synthesis
[[concepts/models|Models]] serve as mathematical or statistical representations that capture relationships among variables in systems ranging from evolutionary processes to disease dynamics, with their utility established across diverse scientific domains. Across these applications, a fundamental mechanistic challenge emerges: models of sufficient complexity to capture biological reality often render traditional likelihood-based [[concepts/inference|inference]] computationally intractable, leading to the development of Approximate Bayesian Computation (ABC) as a simulation-based alternative that replaces direct likelihood evaluation with comparison of observed and simulated data through [[concepts/summary statistics|summary statistics]]. The framework enables both [[concepts/parameter estimation|parameter estimation]] and [[concepts/model selection|model selection]] by allowing researchers to fit different candidate models and compare their performance within a Bayesian inferential context. However, significant tensions remain unresolved regarding the optimal balance between model complexity and inferential precision, as evidenced by ongoing debates about whether simple models can adequately capture phenomena like [[concepts/tumor|tumor]] heterogeneity and the dual roles of [[concepts/chromosomal instability|chromosomal instability]], where the same genomic alterations can act as both [[concepts/oncogenic|oncogenic]] drivers and tumor suppressors depending on context.
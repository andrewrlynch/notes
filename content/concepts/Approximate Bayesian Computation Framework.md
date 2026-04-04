---
cluster: true
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members:
- '[[concepts/accuracy|accuracy]]'
- '[[concepts/algorithms|algorithms]]'
- '[[concepts/approximate bayesian computation (abc)|approximate bayesian computation
  (abc)]]'
- '[[concepts/bayesian analysis|bayesian analysis]]'
- '[[concepts/complex models|complex models]]'
- '[[concepts/cross validation|cross validation]]'
- '[[concepts/data simulation|data simulation]]'
- '[[concepts/inference|inference]]'
- '[[concepts/likelihood function|likelihood function]]'
- '[[concepts/model selection|model selection]]'
- '[[concepts/models|models]]'
- '[[concepts/nonlinear heteroscedastic regression|nonlinear heteroscedastic regression]]'
- '[[concepts/parameter estimation|parameter estimation]]'
- '[[concepts/summary statistics|summary statistics]]'
modified: '2026-03-31'
order: 2
sources: []
synthesis_status: none
tags: []
title: Approximate Bayesian Computation Framework
type: concept
---

Approximate Bayesian Computation (ABC) has emerged as a powerful framework for [[concepts/parameter estimation|parameter estimation]] and [[concepts/model selection|model selection]] when working with [[concepts/complex models|complex models]] where likelihood functions are intractable or computationally prohibitive. The established foundation rests on [[concepts/bayesian analysis|Bayesian analysis]] principles that combine prior beliefs with observed data to produce posterior distributions, but ABC circumvents the need for explicit likelihood evaluation by instead relying on [[concepts/data simulation|data simulation]] and comparison of [[concepts/summary statistics|summary statistics]]. This approach has proven particularly valuable for complex [[concepts/models|models]] where generating synthetic data is feasible even when calculating exact likelihoods is not, enabling [[concepts/inference|inference]] across domains from population genetics to systems biology.

The key mechanistic picture involves generating simulated datasets from candidate models with varying parameter values, computing summary statistics that capture essential features of both observed and simulated data, and accepting parameter values when the simulated statistics are sufficiently close to observed statistics according to some distance [[concepts/metric|metric]] and tolerance threshold. [[concepts/algorithms|Algorithms]] implementing ABC vary in their strategies for proposing parameters, from simple rejection sampling to more sophisticated sequential Monte Carlo approaches, and generalist ABC packages now accommodate flexible choices of both models and algorithms. The [[concepts/accuracy|accuracy]] of parameter estimates depends critically on the choice of summary statistics, which must balance informativeness against dimensionality, and on tolerance settings that trade computational efficiency against approximation quality.

Several aspects remain contested or unresolved in the ABC framework. The selection of appropriate summary statistics remains largely problem-specific and ad hoc, though recent work on [[concepts/nonlinear heteroscedastic regression|nonlinear heteroscedastic regression]] has shown promise for improving parameter estimation accuracy by learning optimal weighting schemes. [[concepts/cross validation|Cross validation]] techniques offer one approach to evaluating model performance and accuracy, but consensus on best practices for ABC validation is still developing. The fundamental tension between using sufficiently informative summary statistics while avoiding the curse of dimensionality continues to challenge practitioners, as does the question of how tolerance thresholds should be optimally chosen across different problem domains.

## Member Concepts
- [[concepts/accuracy|accuracy]]
- [[concepts/algorithms|algorithms]]
- [[concepts/approximate bayesian computation (abc)|approximate bayesian computation (abc)]]
- [[concepts/bayesian analysis|bayesian analysis]]
- [[concepts/complex models|complex models]]
- [[concepts/cross validation|cross validation]]
- [[concepts/data simulation|data simulation]]
- [[concepts/inference|inference]]
- [[concepts/likelihood function|likelihood function]]
- [[concepts/model selection|model selection]]
- [[concepts/models|models]]
- [[concepts/nonlinear heteroscedastic regression|nonlinear heteroscedastic regression]]
- [[concepts/parameter estimation|parameter estimation]]
- [[concepts/summary statistics|summary statistics]]

## Tensions
- **summary statistics vs accuracy:** Summary statistics must reduce high-dimensional data to manageable dimensions for computational tractability, yet this reduction necessarily discards information that could improve parameter estimation accuracy. Achieving high accuracy requires maximally informative statistics, but increasing the number or complexity of summary statistics exacerbates the curse of dimensionality and can paradoxically worsen ABC performance. Resolving this tension requires principled methods for selecting or learning optimal low-dimensional sufficient statistics.
- **data simulation vs likelihood function:** ABC treats data simulation as a substitute for likelihood evaluation, assuming that matching summary statistics of simulated and observed data provides adequate approximation to the true posterior. However, this simulation-based approach can fail to capture the full information content that likelihood functions encode, particularly when summary statistics are insufficient. Resolving this tension would require either demonstrating conditions under which summary statistics are sufficient or developing methods to quantify and correct for information loss.
- **model selection vs parameter estimation:** ABC is used for both parameter estimation within models and selection among competing models, but the optimal choice of summary statistics and tolerance thresholds typically differs between these two tasks. Statistics that discriminate well between models may not be most informative for parameter estimation within a model, and tolerance settings that work for parameter inference may be inappropriate for model comparison. Resolving this requires either task-specific ABC implementations or unified frameworks that can simultaneously optimize for both objectives.

## Open Questions
- How can summary statistics be systematically selected or learned to maximize information content while maintaining computational tractability across diverse problem domains?
- What are the theoretical guarantees on the accuracy of ABC parameter estimates as a function of tolerance threshold, summary statistic choice, and sample size?
- How should tolerance thresholds be adaptively chosen to optimally balance computational cost against approximation error for different types of inference problems?
- Can cross validation or other model evaluation techniques provide reliable guidance for selecting among different ABC algorithms and tuning their hyperparameters?
- Under what conditions do ABC posterior approximations based on summary statistics converge to true Bayesian posteriors, and how can convergence be assessed in practice?
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
- '[@colijn_metric_2018]'
synthesis_status: draft
tags: []
title: Metric on tree shapes groups phylogenetically similar trees
type: concept
---

A [[concepts/metric|metric]] derived from [[concepts/node labeling|node labeling]] schemes can compare tree shapes based on the intuition that trees are similar when they share many subtrees with identical labels. This metric successfully groups trees from the same random evolutionary process together in [[concepts/multidimensional scaling|multidimensional scaling]] plots while distinguishing between trees from different stochastic processes. [@colijn_metric_2018]

## Definitions
- [[concepts/metric|metric]]
- [[concepts/tree shape|tree shape]]
- [[concepts/node labeling|node labeling]]
- [[concepts/subtree|subtree]]
- [[concepts/multidimensional scaling|multidimensional scaling]]
- [[concepts/node label|node label]]

## Synthesis
Phylogenetic metrics based on [[concepts/node labeling|node labeling]] schemes provide a mathematical framework for quantifying distances between tree shapes, exploiting the principle that [[concepts/root node|root node]] labels uniquely encode [[concepts/binary tree|binary tree]] topology through systematic characterization of [[concepts/subtree|subtree]] structures. When applied to trees generated from different stochastic evolutionary [[concepts/models|models]], these metrics successfully group trees by their underlying generative processes, distinguishing birth-death models from Yule and Aldous models more effectively than simple [[concepts/summary statistics|summary statistics]] like [[concepts/tree imbalance|tree imbalance]]. The approach leverages structural features such as [[concepts/cherry|cherry]] subtree frequencies, which relate directly to overall [[concepts/tree asymmetry|tree asymmetry]] and can be linked mechanistically to parameters like the [[concepts/basic reproduction number|basic reproduction number]]. While the [[concepts/metric|metric]] demonstrably separates trees from distinct evolutionary scenarios, the specific topological features that best capture subtle differences between similar generative processes remain an active area of investigation.

## Related
- [[concepts/Tree asymmetry relates to frequency of symmetric cherry subtrees|Tree asymmetry relates to frequency of symmetric cherry subtrees]]
- [[concepts/Phylogenetic metrics distinguish trees from different generative processes|Phylogenetic metrics distinguish trees from different generative processes]]
- [[concepts/Root node label uniquely defines binary tree shape|Root node label uniquely defines binary tree shape]]

## Bibliography
- [[summaries/colijn-metric-2018|A Metric on Phylogenetic Tree Shapes]]
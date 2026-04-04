---
cluster: true
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members:
- '[[concepts/asexual population|asexual population]]'
- '[[concepts/branching pattern|branching pattern]]'
- '[[concepts/circulating|circulating]]'
- '[[concepts/evolution|evolution]]'
- '[[concepts/evolutionary prediction|evolutionary prediction]]'
- '[[concepts/fitness|fitness]]'
- '[[concepts/fitness variation|fitness variation]]'
- '[[concepts/genealogical pattern|genealogical pattern]]'
- '[[concepts/influenza AH3N2 virus|influenza A/H3N2 virus]]'
- '[[concepts/influenza season|influenza season]]'
- '[[concepts/lineage|lineage]]'
- '[[concepts/progenitor lineage|progenitor lineage]]'
- '[[concepts/relative fitness|relative fitness]]'
- '[[concepts/seasonal influenza|seasonal influenza]]'
- '[[concepts/selection pressure|selection pressure]]'
- '[[concepts/sequence|sequence]]'
- '[[concepts/small effect mutations|small effect mutations]]'
- '[[concepts/strain|strain]]'
modified: '2026-03-31'
order: 2
sources: []
synthesis_status: none
tags: []
title: Evolutionary dynamics of asexual populations
type: concept
---

Asexual populations, including rapidly evolving pathogens like [[concepts/influenza AH3N2 virus|influenza A/H3N2 virus]], accumulate [[concepts/genetic variation|genetic variation]] exclusively through mutations along single lineages of descent, creating genealogical trees that record the history of evolutionary change. These populations exhibit persistent [[concepts/fitness variation|fitness variation]] among [[concepts/circulating|circulating]] strains, with some lineages possessing consistently higher [[concepts/relative fitness|relative fitness]] that enables them to outcompete others during successive influenza seasons. The branching patterns of genealogical trees reflect these underlying [[concepts/fitness|fitness]] differences, as more fit lineages produce more descendants and occupy larger portions of the tree structure. This relationship between tree topology and fitness has enabled [[concepts/evolutionary prediction|evolutionary prediction]], where analysis of current genealogical patterns can identify progenitor lineages that will give rise to successful strains in future seasons. The predictive power stems from the observation that fitness variation is not merely transient noise but reflects heritable differences that persist as lineages evolve under [[concepts/selection pressure|selection pressure]]. [[concepts/small effect mutations|Small effect mutations]] accumulate during viral [[concepts/evolution|evolution]], each contributing minimally to fitness but collectively driving the selective dynamics that shape which strains remain circulating in the population. The mechanistic picture connects [[concepts/sequence|sequence]]-level changes to genealogical structure to population-level outcomes, forming a framework for understanding evolution in real time. However, several aspects remain contested, including the extent to which genealogical patterns alone can capture the full complexity of fitness landscapes, the role of epistatic interactions among mutations, and whether predictions trained on one pathogen or population generalize to others with different evolutionary constraints.

## Member Concepts
- [[concepts/asexual population|asexual population]]
- [[concepts/branching pattern|branching pattern]]
- [[concepts/circulating|circulating]]
- [[concepts/evolution|evolution]]
- [[concepts/evolutionary prediction|evolutionary prediction]]
- [[concepts/fitness|fitness]]
- [[concepts/fitness variation|fitness variation]]
- [[concepts/genealogical pattern|genealogical pattern]]
- [[concepts/influenza AH3N2 virus|influenza A/H3N2 virus]]
- [[concepts/influenza season|influenza season]]
- [[concepts/lineage|lineage]]
- [[concepts/progenitor lineage|progenitor lineage]]
- [[concepts/relative fitness|relative fitness]]
- [[concepts/seasonal influenza|seasonal influenza]]
- [[concepts/selection pressure|selection pressure]]
- [[concepts/sequence|sequence]]
- [[concepts/small effect mutations|small effect mutations]]
- [[concepts/strain|strain]]

## Tensions
- **small effect mutations vs persistent fitness variation:** Small effect mutations are expected to produce minimal individual fitness differences, yet persistent fitness variation requires that lineages maintain distinguishable fitness advantages across multiple seasons. This tension raises questions about whether fitness differences arise from the cumulative effects of many small mutations, rare large-effect mutations that are missed by characterization, or epistatic interactions that amplify small effects. Resolving this would require quantifying the distribution of fitness effects and their temporal stability.
- **genealogical pattern vs evolutionary prediction:** Genealogical patterns are historical records of past evolutionary events, while evolutionary prediction requires inferring future dynamics from current data. The tension lies in whether tree topology contains sufficient forward-looking information to overcome the inherent stochasticity of mutation, drift, and environmental change that could decouple past patterns from future outcomes. Resolution would require demonstrating which features of genealogies are predictive versus merely descriptive.
- **asexual population vs fitness variation:** In asexual populations, all descendants of a high-fitness lineage inherit that fitness advantage through clonal reproduction, which should lead to rapid selective sweeps that purge fitness variation. However, persistent fitness variation requires that multiple distinct lineages with different fitnesses coexist simultaneously. This tension can only be resolved if new mutations arise fast enough, or if environmental heterogeneity or frequency-dependent selection maintains diversity despite clonal interference.

## Open Questions
- What proportion of fitness variation in seasonal influenza is explained by small effect mutations versus rare large effect mutations?
- How far into the future can genealogical tree analysis reliably predict successful lineages before stochastic effects dominate?
- Do the relationships between tree topology and fitness generalize across different asexual populations or are they specific to influenza virus evolution?
- What mechanisms maintain persistent fitness variation in asexual populations despite the expectation of rapid selective sweeps?
- Can genealogical prediction methods account for epistatic interactions among mutations or do they assume additive fitness effects?
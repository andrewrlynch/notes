---
cluster: true
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members:
- '[[concepts/Aneuploidy causes proliferative disadvantage independent of extra chromosome
  identity|Aneuploidy causes proliferative disadvantage independent of extra chromosome
  identity]]'
- '[[concepts/Aneuploidy heightens sensitivity to protein synthesis interference|Aneuploidy
  heightens sensitivity to protein synthesis interference]]'
- '[[concepts/Aneuploidy impairs cell cycle progression in haploid yeast|Aneuploidy
  impairs cell cycle progression in haploid yeast]]'
- '[[concepts/Aneuploidy increases glucose uptake in yeast cells|Aneuploidy increases
  glucose uptake in yeast cells]]'
- '[[concepts/Extra chromosome genes drive aneuploid phenotypes through imbalanced
  protein composition|Extra chromosome genes drive aneuploid phenotypes through imbalanced
  protein composition]]'
modified: '2026-03-31'
order: 3
sources: []
synthesis_status: none
tags: []
title: Aneuploidy imposes a universal proteotoxic stress through stoichiometric imbalance
type: concept
---

Aneuploidy in yeast produces a remarkably consistent set of phenotypes regardless of which specific chromosome is duplicated, suggesting that the burden arises from a general consequence of chromosome gain rather than from specific [[concepts/gene dosage|gene dosage]] effects. The [[concepts/proliferative disadvantage|proliferative disadvantage]], cell cycle delays, and heightened [[concepts/sensitivity|sensitivity]] to protein synthesis inhibitors all point to a common underlying mechanism: the [[concepts/aneuploid|aneuploid]] cell struggles to maintain proteostasis in the face of systematically imbalanced [[concepts/gene expression|gene expression]]. When an entire chromosome is duplicated, hundreds of genes are overexpressed simultaneously, and the resulting proteins must be synthesized, folded, and incorporated into multi-subunit complexes that also contain subunits encoded by chromosomes present in normal [[concepts/copy number|copy number]]. This stoichiometric mismatch creates an excess of unpartnered protein subunits that burden the protein quality control machinery, triggering a proteotoxic stress response. The increased [[concepts/glucose uptake|glucose uptake]] observed in aneuploid strains likely reflects a compensatory metabolic shift to meet the elevated energy demands of increased protein synthesis and degradation, as well as the activation of stress response pathways. The mechanistic link between gene dosage imbalance and cellular [[concepts/phenotype|phenotype]] is direct: the genes on the extra chromosome are expressed, their protein products accumulate in proportion to gene copy number, and the resulting compositional imbalance in the [[concepts/proteome|proteome]] drives the observed defects. This model predicts that any perturbation that further challenges protein homeostasis—such as inhibitors of translation, chaperones, or proteasomes—will be particularly detrimental to [[concepts/aneuploid cells|aneuploid cells]], which are already operating near the limits of their proteostasis capacity.

## Member Concepts
- [[concepts/Aneuploidy causes proliferative disadvantage independent of extra chromosome identity|Aneuploidy causes proliferative disadvantage independent of extra chromosome identity]]
- [[concepts/Aneuploidy heightens sensitivity to protein synthesis interference|Aneuploidy heightens sensitivity to protein synthesis interference]]
- [[concepts/Aneuploidy impairs cell cycle progression in haploid yeast|Aneuploidy impairs cell cycle progression in haploid yeast]]
- [[concepts/Aneuploidy increases glucose uptake in yeast cells|Aneuploidy increases glucose uptake in yeast cells]]
- [[concepts/Extra chromosome genes drive aneuploid phenotypes through imbalanced protein composition|Extra chromosome genes drive aneuploid phenotypes through imbalanced protein composition]]

## Tensions
- **Universal proliferative disadvantage vs Chromosome-specific gene content:** If different chromosomes carry genes with distinct functions, one would expect the phenotypic consequences of duplicating different chromosomes to vary substantially. Yet the observation that all aneuploid strains exhibit similar proliferative defects suggests a chromosome-identity-independent mechanism dominates. Resolving this tension requires determining whether certain chromosomes do produce unique phenotypes that are masked by the common proteotoxic stress, or whether stoichiometric imbalance truly overwhelms any gene-specific effects.
- **Increased glucose uptake as compensation vs Proliferative disadvantage despite metabolic adaptation:** Aneuploid cells increase glucose uptake, presumably to fuel the additional energetic costs of dealing with protein imbalance, yet they still grow more slowly than euploid cells. This raises the question of whether the metabolic response is insufficient to fully compensate for the proteotoxic burden, or whether the metabolic reprogramming itself has fitness costs. Understanding this tension requires quantifying whether aneuploidy creates an insurmountable energetic deficit or whether other rate-limiting factors prevent growth recovery.
- **Proteotoxic stress as primary driver vs Cell cycle defects as direct consequence:** While proteotoxic stress could indirectly impair cell cycle progression through checkpoint activation or resource depletion, it is also possible that specific cell cycle regulators encoded on extra chromosomes are directly responsible for cell cycle delays through dosage-sensitive effects. Distinguishing between these scenarios requires demonstrating whether cell cycle defects can be rescued by alleviating proteotoxic stress without normalizing the expression of cell cycle genes.

## Open Questions
- Does the severity of aneuploid phenotypes scale linearly with the number of genes on the extra chromosome, or do certain chromosomes impose disproportionate burdens?
- Can experimentally reducing protein synthesis rates in aneuploid cells paradoxically improve fitness by reducing proteotoxic stress, or does this further limit growth?
- What fraction of the energetic cost in aneuploid cells is attributable to increased protein synthesis versus increased protein degradation and quality control?
- Do aneuploid cells with different extra chromosomes activate the same stress response pathways, or are there chromosome-specific transcriptional signatures beyond the shared proteotoxic response?
- Can overexpression of specific chaperones or proteasome components rescue aneuploid phenotypes, and if so, which components of the proteostasis network are most rate-limiting?
---
cluster: true
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members:
- '[[concepts/biological mechanism|biological mechanism]]'
- '[[concepts/breast cancer outcome|breast cancer outcome]]'
- '[[concepts/cell cycle genes|cell cycle genes]]'
- '[[concepts/cell proliferation|cell proliferation]]'
- '[[concepts/confounding|confounding]]'
- '[[concepts/confounding effect|confounding effect]]'
- '[[concepts/confounding variables|confounding variables]]'
- '[[concepts/gene expression marker|gene expression marker]]'
- '[[concepts/hazard ratio|hazard ratio]]'
- '[[concepts/metagene|metagene]]'
- '[[concepts/outcome association|outcome association]]'
- '[[concepts/outcome predictor|outcome predictor]]'
- '[[concepts/proliferation marker|proliferation marker]]'
- '[[concepts/random signature|random signature]]'
- '[[concepts/statistical association|statistical association]]'
- '[[concepts/statistical significance|statistical significance]]'
- '[[concepts/transcriptome|transcriptome]]'
modified: '2026-03-31'
order: 2
sources: []
synthesis_status: none
tags: []
title: Proliferation confounding in gene signatures
type: concept
---

[[concepts/gene expression|Gene expression]] signatures derived from [[concepts/tumor|tumor]] transcriptomes are widely used as outcome predictors in breast [[concepts/cancer|cancer]], with many signatures showing statistically significant associations with disease recurrence and survival. These signatures typically consist of multiple genes whose combined expression levels, often summarized as a [[concepts/metagene|metagene]], correlate with clinical outcomes and generate measurable hazard ratios that inform prognosis. The [[concepts/biological mechanism|biological mechanism]] presumed to link gene signatures to outcome is that they capture specific disease-relevant molecular processes operating within [[concepts/tumor cells|tumor cells]].

A critical challenge has emerged regarding whether these outcome associations genuinely indicate the biological relevance of the specific pathways that signatures purport to measure. [[concepts/cell proliferation|Cell proliferation]] represents a fundamental [[concepts/confounding|confounding]] variable because it strongly predicts [[concepts/breast cancer outcome|breast cancer outcome]] while also influencing the expression of large portions of the [[concepts/transcriptome|transcriptome]]. Remarkably, most random gene signatures—constructed by selecting genes without regard to any particular biological process—show significant associations with breast cancer outcome, calling into question whether observed statistical associations reflect the action of specific biological mechanisms or simply capture variance related to proliferation markers.

The extent to which [[concepts/cell cycle genes|cell cycle genes]] drive this [[concepts/confounding effect|confounding effect]] remains contested. Attempts to remove cell cycle genes from signatures or analyses have failed to eliminate the proliferation-related confounding, suggesting that proliferation influences gene expression more broadly than just through canonical cell cycle regulators. This raises fundamental questions about how to distinguish meaningful biological signals from confounding effects when proliferation is both a genuine driver of outcome and a pervasive influence on the transcriptome. The field has yet to establish robust criteria for determining when a [[concepts/gene expression marker|gene expression marker]] represents a distinct biological mechanism versus when it merely serves as another [[concepts/proliferation marker|proliferation marker]].

## Member Concepts
- [[concepts/biological mechanism|biological mechanism]]
- [[concepts/breast cancer outcome|breast cancer outcome]]
- [[concepts/cell cycle genes|cell cycle genes]]
- [[concepts/cell proliferation|cell proliferation]]
- [[concepts/confounding|confounding]]
- [[concepts/confounding effect|confounding effect]]
- [[concepts/confounding variables|confounding variables]]
- [[concepts/gene expression marker|gene expression marker]]
- [[concepts/hazard ratio|hazard ratio]]
- [[concepts/metagene|metagene]]
- [[concepts/outcome association|outcome association]]
- [[concepts/outcome predictor|outcome predictor]]
- [[concepts/proliferation marker|proliferation marker]]
- [[concepts/random signature|random signature]]
- [[concepts/statistical association|statistical association]]
- [[concepts/statistical significance|statistical significance]]
- [[concepts/transcriptome|transcriptome]]

## Tensions
- **gene expression marker as biological mechanism indicator vs proliferation as confounding variable:** Gene expression markers are intended to reflect specific biological mechanisms relevant to disease, yet proliferation acts as a confounding variable that correlates with both gene expression patterns and clinical outcomes. This creates the tension that statistically significant outcome associations may not indicate the biological relevance of the specific mechanism a signature claims to measure, but rather reflect the pervasive influence of cell proliferation on the transcriptome. Resolving this would require methods to definitively separate proliferation-independent biological signals from proliferation-driven associations.
- **cell cycle gene removal as deconfounding strategy vs persistent proliferation confounding after cell cycle gene removal:** One might expect that removing cell cycle genes from signatures would eliminate proliferation confounding, since these genes directly regulate cell division. However, empirical evidence shows that cell cycle gene removal fails to eliminate the confounding effect, suggesting proliferation influences gene expression more broadly. This tension highlights uncertainty about which genes constitute true proliferation markers versus those regulated by other mechanisms. Resolution would require comprehensive mapping of all proliferation-responsive genes across the transcriptome.
- **statistical significance as evidence threshold vs random signature outcome associations:** Statistical significance is conventionally used to distinguish meaningful associations from chance findings, providing a threshold for inferring biological relevance. However, most random gene signatures achieve statistical significance when tested for breast cancer outcome association, demonstrating that this threshold alone is insufficient. The tension arises because the statistical framework assumes independence that does not hold when confounding variables pervade the data structure. Resolving this requires developing alternative statistical criteria that account for the correlation structure imposed by proliferation.

## Open Questions
- What proportion of genes in the transcriptome are influenced by proliferation rate, either directly or indirectly?
- Can any gene expression signature demonstrate outcome association that is genuinely independent of proliferation confounding in breast cancer?
- What statistical or experimental methods can definitively distinguish whether an outcome association reflects a specific biological mechanism versus proliferation confounding?
- Why does removal of canonical cell cycle genes fail to eliminate proliferation-related confounding in gene signature analyses?
- Do random gene signatures show similar outcome associations in cancers where proliferation is less dominant as a prognostic factor?
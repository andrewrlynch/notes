---
cluster: true
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members:
- '[[concepts/aneuploid yeast|aneuploid yeast]]'
- '[[concepts/chromosomal position|chromosomal position]]'
- '[[concepts/chromosome loss|chromosome loss]]'
- '[[concepts/disomic strains|disomic strains]]'
- '[[concepts/duplicated chromosomes|duplicated chromosomes]]'
- '[[concepts/gene dosage|gene dosage]]'
- '[[concepts/growth medium|growth medium]]'
- '[[concepts/liquid chromatography—tandem mass spectrometry|liquid chromatography—tandem
  mass spectrometry]]'
- '[[concepts/log2 ratios|log2 ratios]]'
- '[[concepts/open reading frames|open reading frames]]'
- '[[concepts/protein abundance|protein abundance]]'
- '[[concepts/proteome|proteome]]'
- '[[concepts/silac|silac]]'
- '[[concepts/wild type cells|wild type cells]]'
modified: '2026-03-31'
order: 2
sources: []
synthesis_status: none
tags: []
title: Proteome consequences of aneuploidy
type: concept
---

Aneuploidy, the presence of an abnormal number of chromosomes in cells, has been systematically studied in yeast using quantitative proteomics approaches such as [[concepts/silac|SILAC]] and liquid chromatography-tandem mass spectrometry to measure [[concepts/protein abundance|protein abundance]] changes. These techniques can quantify approximately 70-80% of yeast [[concepts/open reading frames|open reading frames]], enabling comprehensive assessment of how chromosome gain or loss affects the cellular [[concepts/proteome|proteome]]. [[concepts/disomic strains|Disomic strains]] containing an extra copy of individual chromosomes provide controlled experimental systems for studying the proteome-wide effects of altered [[concepts/gene dosage|gene dosage]] compared to [[concepts/wild type cells|wild type cells]].

The mechanistic relationship between chromosome [[concepts/copy number|copy number]] and protein abundance shows that [[concepts/Aneuploidy alters cellular protein composition approximately twofold|aneuploidy alters cellular protein composition approximately twofold]] in proportion to gene dosage, meaning that proteins encoded on [[concepts/duplicated chromosomes|duplicated chromosomes]] generally increase by roughly two-fold. This dosage-dependent protein level change can be measured using [[concepts/log2 ratios|log2 ratios]] comparing [[concepts/aneuploid|aneuploid]] to wild type samples. However, the relationship between gene dosage and protein abundance is not uniform across the genome, as [[concepts/Protein levels correlate with chromosomal position in aneuploid strains|protein levels correlate with chromosomal position in aneuploid strains]], suggesting that local chromatin context or chromosome structure influences expression. The extra chromosome genes themselves appear to drive aneuploid phenotypes through their cumulative effects on cellular composition.

Important questions remain about the extent to which environmental factors modulate these protein changes, as [[concepts/Growth medium conditions affect aneuploid strain proteome composition|growth medium conditions affect aneuploid strain proteome composition]]. The mechanisms underlying positional effects on protein abundance are not fully understood, nor is it clear how cells buffer or fail to buffer against the widespread stoichiometric imbalances created by aneuploidy. Additionally, the relationship between [[concepts/chromosome loss|chromosome loss]] and protein depletion has been less systematically characterized than chromosome gain.

## Member Concepts
- [[concepts/aneuploid yeast|aneuploid yeast]]
- [[concepts/chromosomal position|chromosomal position]]
- [[concepts/chromosome loss|chromosome loss]]
- [[concepts/disomic strains|disomic strains]]
- [[concepts/duplicated chromosomes|duplicated chromosomes]]
- [[concepts/gene dosage|gene dosage]]
- [[concepts/growth medium|growth medium]]
- [[concepts/liquid chromatography—tandem mass spectrometry|liquid chromatography—tandem mass spectrometry]]
- [[concepts/log2 ratios|log2 ratios]]
- [[concepts/open reading frames|open reading frames]]
- [[concepts/protein abundance|protein abundance]]
- [[concepts/proteome|proteome]]
- [[concepts/silac|silac]]
- [[concepts/wild type cells|wild type cells]]

## Tensions
- **gene dosage vs chromosomal position:** Gene dosage predicts that protein levels should scale uniformly with chromosome copy number across all genes on a duplicated chromosome. However, chromosomal position effects create variability in this relationship, suggesting that location-dependent factors such as chromatin structure or nuclear organization modulate the translation of gene copy number into protein abundance. Resolving this tension requires understanding which positional features override simple dosage expectations and under what conditions.
- **protein abundance vs growth medium:** Protein abundance in aneuploid strains is expected to directly reflect the altered gene dosage from extra or missing chromosomes. Yet growth medium conditions can substantially affect the proteome composition of aneuploid strains, indicating that environmental factors modulate how chromosome copy number translates into protein levels. This suggests either compensatory mechanisms or metabolic constraints that are condition-dependent, but the relative contribution of intrinsic dosage effects versus environmental modulation remains unclear.
- **disomic strains vs wild type cells:** Disomic strains serve as controlled models for understanding how single chromosome duplications affect cellular physiology compared to wild type cells. However, the comparison assumes that the primary difference is the extra chromosome, while the phenotypic consequences of aneuploidy may involve complex compensatory responses, stress pathways, or selection for suppressor mutations that confound simple interpretation. Determining whether observed proteome changes represent direct dosage effects or secondary adaptations requires distinguishing immediate from evolved responses.

## Open Questions
- What specific chromosomal position features determine the extent to which proteins deviate from predicted gene dosage effects in aneuploid cells?
- How do different growth medium conditions mechanistically alter the relationship between chromosome copy number and protein abundance?
- Do cells possess active buffering mechanisms that partially compensate for dosage imbalances, or do the approximately twofold changes represent passive consequences of gene copy number?
- How does chromosome loss affect protein depletion patterns compared to the relatively well-characterized effects of chromosome gain?
- What is the relative contribution of transcriptional versus post-transcriptional mechanisms in mediating the proteome changes observed in aneuploid strains?
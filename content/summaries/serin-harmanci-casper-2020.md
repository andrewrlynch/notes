---
authors: Serin Harmanci, Akdes and Harmanci, Arif O. and Zhou, Xiaobo
citekey: serin_harmanci_casper_2020
created: '2026-03-31'
createdBy: fossick
doi: 10.1038/s41467-019-13779-x
fulltext_source: pmc
journal: Nature Communications
modified: '2026-03-31'
pmcid: ''
pmid: ''
tags:
- summary
title: CaSpER identifies and visualizes CNV events by integrative analysis of single-cell
  or bulk RNA-sequencing data
type: summary
year: 2020
---

# CaSpER identifies and visualizes CNV events by integrative analysis of single-cell or bulk RNA-sequencing data

**Authors:** Serin Harmanci, Akdes and Harmanci, Arif O. and Zhou, Xiaobo
**Year:** 2020
**Journal:** Nature Communications

## Abstract

RNA sequencing experiments generate large amounts of information about expression levels of genes. Although they are mainly used for quantifying expression levels, they contain much more biologically important information such as copy number variants (CNVs). Here, we present CaSpER, a signal processing approach for identification, visualization, and integrative analysis of focal and large-scale CNV events in multiscale resolution using either bulk or single-cell RNA sequencing data. CaSpER integrates the multiscale smoothing of expression signal and allelic shift signals for CNV calling. The allelic shift signal measures the loss-of-heterozygosity (LOH) which is valuable for CNV identification. CaSpER employs an efficient methodology for the generation of a genome-wide B-allele frequency (BAF) signal profile from the reads and utilizes it for correction of CNVs calls. CaSpER increases the utility of RNA-sequencing datasets and complements other tools for complete characterization and visualization of the genomic and transcriptomic landscape of single cell and bulk RNA sequencing data.

## Notes

## Extracted Concepts
- [[concepts/BAF generation from RNA-seq reads does not require prior variant calls|BAF generation from RNA-seq reads does not require prior variant calls]]
- [[concepts/CaSpER algorithm uses expression and BAF values to estimate CNV events|CaSpER algorithm uses expression and BAF values to estimate CNV events]]
- [[concepts/Five-state HMM assigns copy number states and segments genomic regions|Five-state HMM assigns copy number states and segments genomic regions]]
- [[concepts/Multiscale BAF smoothing improves CNV call assignment accuracy|Multiscale BAF smoothing improves CNV call assignment accuracy]]
- [[concepts/Recursive median filtering and multiscale decomposition smooth expression signal noise|Recursive median filtering and multiscale decomposition smooth expression signal noise]]
- [[concepts/Strong expression signal events require no BAF corroboration for CNV calls|Strong expression signal events require no BAF corroboration for CNV calls]]
- [[concepts/Weak expression signal events require BAF shifts for CNV confirmation|Weak expression signal events require BAF shifts for CNV confirmation]]
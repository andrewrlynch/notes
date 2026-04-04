---
cluster: false
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members: []
modified: '2026-03-31'
order: 2
sources:
- '[@serin_harmanci_casper_2020]'
synthesis_status: none
tags: []
title: CaSpER algorithm uses expression and BAF values to estimate CNV events
type: concept
---

CaSpER integrates normalized [[concepts/gene expression|gene expression]] values and B-allele frequencies (BAF) extracted from RNA-seq reads to estimate copy number variation events. The algorithm treats expression values as a genome-wide signal profile and BAF as a relative normalized measure of allelic intensity ratios, combining these two independent signals to identify and characterize CNV events across the genome. [@serin_harmanci_casper_2020]

## Definitions
- [[concepts/gene expression|gene expression]]

## Bibliography
- [[summaries/serin-harmanci-casper-2020|CaSpER identifies and visualizes CNV events by integrative analysis of single-cell or bulk RNA-sequencing data]]
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
title: Recursive median filtering and multiscale decomposition smooth expression signal
  noise
type: concept
---

CaSpER eliminates noise in the initial expression signal profile by applying sliding window-based median filtering and computing N-level multiscale decomposition at multiple window length scales. The window length increases between consecutive scales so that higher scales correspond to more extensively smoothed signal compared to smaller scales, creating a multi-resolution representation of the expression data. [@serin_harmanci_casper_2020]

## Definitions
- [[concepts/in vitro|in vitro]]

## Bibliography
- [[summaries/serin-harmanci-casper-2020|CaSpER identifies and visualizes CNV events by integrative analysis of single-cell or bulk RNA-sequencing data]]
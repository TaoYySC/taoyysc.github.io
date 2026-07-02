---
title: "PhosLoc-Transport"
excerpt: "A direction-aware framework links transcription factor phosphosites to localization and transcriptional output."
collection: portfolio
---

**PhosLoc-Transport** is a two-stage computational framework for prioritizing transcription factor phosphosites that may regulate nuclear transport.

**GitHub:** [https://github.com/TaoYySC/phosloc-transport](https://github.com/TaoYySC/phosloc-transport)

## Overview

The framework combines sequence-based and structure-aware machine learning to connect phosphorylation sites with subcellular localization changes and downstream transcriptional regulation.

| Module | Task |
|--------|------|
| Localization-Regulatory Classifier | Identifies candidate localization-regulatory phosphosites |
| Localization Direction Classifier | Predicts nuclear accumulation vs. cytoplasmic redistribution |
| CPTAC analysis | Validates predicted nuclear accumulation-associated sites |

## Key features

- Integrates local sequence, central phosphosite, and AlphaFold-derived structural features
- Two-stage prediction pipeline for regulatory potential and localization direction
- CPTAC-based validation against tumor multi-omics target-gene regulation
- Reproducible training, prediction, and analysis workflows with documented run settings

## Associated work

Associated manuscript: *A direction-aware framework links transcription factor phosphosites to localization and transcriptional output*.

Processed data and model artifacts are available on [Zenodo (DOI: 10.5281/zenodo.21064685)](https://doi.org/10.5281/zenodo.21064685).

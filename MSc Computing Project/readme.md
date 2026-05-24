# MSc project — Comparative AI Governance

## Project title

**Comparative AI Governance: regulatory trends and emerging policy models in the European Union and the United States, leveraging automated AI text-mining analysis**

## Overview

This MSc project examines how EU and US artificial intelligence governance documents position themselves across a regulatory spectrum. The project develops a reproducible NLP-based artefact that analyses selected legislative, policy and strategic documents and maps them across two axes:

- **X-axis:** rights- and citizen-oriented safeguards ↔ innovation
- **Y-axis:** voluntary/soft-law ↔ mandatory/control

The artefact uses dictionary-based NLP techniques, text extraction from PDF documents, tokenisation, lemmatisation, predefined analytical vocabularies and document-level legal-force multipliers.

## Artefact

The artefact is implemented as a reproducible Python/Google Colab notebook. It processes 24 EU and US AI governance documents and generates:

- regulatory spectrum scatter plot;
- four-component vocabulary profile;
- heatmap of component intensity;
- quadrant distribution chart;
- EU and US analytical word clouds;
- top driver terms by jurisdiction;
- vocabulary audit tables;
- reproducible Excel and HTML outputs.

## Final modelling logic

The final version of the artefact is **v1.3**.

No word-level weights are applied. All vocabulary terms and phrases are counted equally. The only weighting mechanism is the document-level legal-force multiplier applied to the mandatory/control count.

## Repository

The full reproducible artefact is available here:

[AI Governance Regulatory Spectrum Artefact v1.3](https://github.com/narchondas/ai-governance-regulatory-spectrum-v1-3)

## Open in Colab

[Open the replication notebook in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/ai-governance-regulatory-spectrum-v1-3/blob/main/notebooks/AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Replication.ipynb)

## Status

This repository forms part of my MSc research in Artificial Intelligence and supports the thesis artefact through a transparent and reproducible implementation.

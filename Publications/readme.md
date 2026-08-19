# 1. Trends and patterns of EU AI governance: A text-mining-supported analysis

Punto y Coma, special issue on AI innovation ecosystems, forthcoming 2026.

## Overview

The article examines the evolution of European Union artificial intelligence governance across three regulatory phases, from the early period of coordination and soft law, through the adoption of binding regulation, and into the subsequent stage of implementation and simplification. Drawing on documentary analysis of eighteen EU instruments, a text-mining artefact developed for the purpose, and interviews with four experts, it identifies the trends and patterns characterising this trajectory and considers the trade-offs arising between innovation, competitiveness and societal protection.

The project develops a reproducible NLP-based artefact that analyses selected legislative, policy and strategic documents and maps them across two axes:

- **X-axis:** rights- and citizen-oriented safeguards ↔ innovation
- **Y-axis:** voluntary/soft-law ↔ mandatory/control

The artefact uses dictionary-based NLP techniques, text extraction from PDF documents, tokenisation, lemmatisation, predefined analytical vocabularies and document-level legal-force multipliers.

## Artefact

The artefact is implemented as a reproducible Python/Google Colab notebook. It processes 18 EU AI governance documents and generates:

- regulatory spectrum scatter plot;
- four-component vocabulary profile;
- heatmap of component intensity;
- quadrant distribution chart;
- EU analytical word clouds;
- top driver terms by jurisdiction;
- vocabulary audit tables;
- reproducible Excel and HTML outputs.

## Final modelling logic

The final version of the artefact is **v1.3**.

No word-level weights are applied. All vocabulary terms and phrases are counted equally. The only weighting mechanism is the document-level legal-force multiplier applied to the mandatory/control count.

## Repository

The full reproducible artefact is available here:

[AI Governance Regulatory Spectrum Artefact v1.3]()

## Open in Colab

[Open the replication notebook in Google Colab](https://colab.research.google.com/drive/1BtrCoPCjLdFZphm986MSrw3xnLneX4nK?usp=sharing)


The reproducible research material accompanying the article, comprising the analytical notebook and the full corpus of eighteen documents, is available at eu-ai-governance-artefact.

<img width="1448" height="1086" alt="ChatGPT Image May 24, 2026, 10_58_33 PM (2)" src="https://github.com/user-attachments/assets/37ed8aa2-4011-475a-b8ba-aa9c09ebf31d" />






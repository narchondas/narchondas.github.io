# MSc project — Comparative AI Governance

## Project title

**Comparative AI Governance: regulatory trends and emerging policy models in the European Union and the United States, leveraging automated AI text-mining analysis**

## Overview

This MSc project examines how EU and US artificial intelligence governance documents position themselves across a regulatory spectrum. The project develops a reproducible NLP-based artefact that analyses selected legislative, policy and strategic documents and maps them across two axes:

- **X-axis:** rights- and citizen-oriented safeguards ↔ innovation
- **Y-axis:** voluntary/soft-law ↔ mandatory/control

The artefact uses dictionary-based NLP techniques, PDF text extraction, tokenisation, lemmatisation, predefined analytical vocabularies and document-level legal-force multipliers.

## AI Governance Regulatory Spectrum Artefact v1.3

The final artefact processes a corpus of 24 EU and US AI governance documents and generates:

- a regulatory spectrum scatter plot;
- a four-component vocabulary profile;
- a heatmap of component intensity;
- a quadrant distribution chart;
- EU and US analytical word clouds;
- top driver terms by jurisdiction;
- document-type comparison charts;
- vocabulary audit tables;
- reproducible Excel and HTML outputs.

## Final modelling logic

The final version of the artefact is **v1.3**.

No word-level weights are applied. All vocabulary terms and phrases are counted equally. The only weighting mechanism is the document-level legal-force multiplier applied to the mandatory/control count.

## Reproducible artefact repository

The full reproducible artefact will be available here:

[AI Governance Regulatory Spectrum Artefact v1.3](https://github.com/narchondas/ai-governance-regulatory-spectrum-v1-3)

## Open in Colab

[Open the replication notebook in Google Colab](https://colab.research.google.com/drive/16RC0ycwxF866B_RKDviYexnJhvZ9ZLsA?usp=sharing)

## Custom test notebook

In addition to the replication notebook, this repository also includes a **custom test notebook**:

`AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test.ipynb`

The purpose of this notebook is different from the replication file. While the replication notebook reproduces the thesis results using the same 24 public EU and US AI governance documents, the custom test notebook allows other researchers to apply the same v1.3 artefact to their own documents.

Researchers can upload their own PDF files, define a simple metadata table, assign each document to a group such as `Group I` or `Group II`, specify the document type and legal-force multiplier, and then run the same analytical pipeline.

The custom notebook produces the same categories of outputs as the thesis artefact, including:

- regulatory spectrum scatter plot;
- four-component vocabulary profile;
- heatmap of component intensity;
- quadrant distribution chart;
- top driver terms by document group;
- slope chart comparing safeguards and innovation;
- document-type comparison chart;
- analytical vocabulary audit tables;
- exported Excel and HTML outputs.

The custom notebook uses the same v1.3 logic:

- no word-level weights;
- all terms and phrases count as one occurrence;
- the document-level legal-force multiplier is applied only to the mandatory/control count;
- the X-axis measures rights/citizen safeguards versus innovation;
- the Y-axis measures voluntary/soft-law versus mandatory/control language.

This version is therefore intended for reuse and experimentation. It allows researchers to test how other AI-related legal, policy, strategic, institutional or organisational documents are positioned on the same regulatory spectrum.

## Custom artefact repository

The full custom artefact will be available here:

[AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test](notebooks/AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test (1).ipynb)

## Open in Colab

[Open the custom arterfact notebook in Google Colab](https://colab.research.google.com/drive/1Q57pGWiLIeZ95LPFXXLLrJE1m4-lyqtv?usp=sharing)

## Status

This page forms part of my MSc learning path and presents the artefact developed for my thesis in Artificial Intelligence.

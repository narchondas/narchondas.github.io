# MSc Computing Project

This is my learning experience from Module 7 of the MSc Artificial Intelligence

<img width="203" height="105" alt="image" src="https://github.com/user-attachments/assets/6f0efbe0-c118-4e22-ad25-283c350627b4" />


Use the following links to navigate to the start of the sections

[1. Learning Outcomes](#learning-outcomes)

[2. Project Title and Research Proposal](#project-title-and-research-proposal)

[3. Software artefact: AI Governance Regulatory Spectrum](#software-artefact-ai-governance-regulatory-spectrum)

[4. Executive Summary](#executive-summary)


## Learning outcomes 

## In the module MSc Computing Project I shall:

-Understand the methods of project planning.

-Investigate ways of identifying, quantifying and mitigating any risks.

-Explore a range of project types and appropriate research methods.

-Develop the concept of a literature review and horizon scanning.

-Engage with the ethical issues associated with my research.

-Understand the issues surrounding intellectual property in research.


## On completion of the module MSc Computing Project, I will be able to:

-Systematically identify research problem(s) within a suitable research topic involving computing.

-Carry out, structure, and present effectively a focused critical and analytical reading and synthesis of accessed information on the topic.

-Articulate the professional, legal, ethical and social issues related to the chosen topic and follow relevant professional codes of conduct.

-Evaluate critically the research conducted and present the resulting artefact as a form of a defence of the research.


[Back to the top](#msc-computing-project)


## Project title and research proposal

**Comparative AI Governance: regulatory trends and emerging policy models in the European Union and the United States, leveraging automated AI text-mining analysis**

<img width="407" height="307" alt="image" src="https://github.com/user-attachments/assets/6d561b18-82fa-46c5-ac13-956bb5be552f" />


**Research summary** 

This thesis proposes a comparative analysis of AI governance in the European Union and the United States, with the objective of identifying and mapping regulatory trends and emerging policy models through the integration of automated AI-supported text-mining analysis. The research seeks to provide an up-to-date comparative assessment of the two predominant AI governance frameworks up to mid-2026. By examining convergences, divergences, and thematic patterns, the study aims to generate a typology of regulatory approaches and to evaluate their broader policy implications. 

In order to operationalise this overarching aim, the research is structured around three principal objectives. First, it will develop a comparative governance mapping of the key regulatory and institutional trends shaping AI policy in both jurisdictions, identifying the structural features, policy instruments, and institutional configurations that characterise each approach. Second, it will propose a structured analytical framework incorporating AI-supported text-mining tools, in order to systematically analyse thematic trends and patterns across relevant policy documents and institutional communications. Third, it will critically assess the extent to which the findings of the abovementioned exercises on the EU and US AI governance, particularly regarding innovation, competitiveness, and the protection of societal and ethical values, are corroborated by the opinions and the perceptions of the experts (e.g., policy officers, academia). 

The rationale for selecting this topic lies in the rapidly evolving nature of AI governance. In the early stages of AI development, jurisdictions demonstrated caution and uncertainty regarding regulatory intervention, reflecting broader questions about the trajectory of the technology. As AI systems have become increasingly embedded in economic and societal structures, regulatory frameworks have begun to crystallise. The EU and the US represent the two leading and contrasting regulatory jurisdictions shaping global AI governance. The EU tends to adopt a rights-centred, risk-based, and precautionary approach, emphasising safeguards, guidelines, and legislative instruments. In contrast, the US has generally favoured an innovation-oriented, market-driven, and sectoral regulatory model. Examining this emerging regulatory contrast and assessing the extent to which it is supported by evidence is essential for understanding its long-term policy implications for innovation, competitiveness, and the protection of societal and ethical values. 

The research addresses a clear gap in the existing literature. Although some comparative analyses exist, they are limited in scope and are not fully up to date. Moreover, there is insufficient triangulation across academic literature, policy documentation, and expert perspectives. Existing studies also make limited use of computational text analysis tools. This thesis responds to these limitations by integrating AI-supported text-mining methods into a structured qualitative comparative framework, thereby enhancing analytical depth and methodological rigour. 


**Research questions**

RQ1 What trends and patterns define EU vs. US AI governance? 

RQ2 Where do their regulatory models converge or diverge, and how do AI text-mining tools help identify these trends? 

RQ3 What benefits, risks, and trade-offs arise for innovation, competitiveness, and societal/ethical protection? 

**Full Research Proposal** 

[Full research proposal](https://drive.google.com/file/d/1UOfMgUMTHHdBV4tzxVvqvVLjuhxuNSn2/view?usp=drive_link)


**Participation Information Sheet and Consent Form for interviewees**

[Participation Information Sheet and Consent Form for interviewees](https://drive.google.com/file/d/1xhCsifUOLv-Fe57gGE5z6AqerKnhpoP3/view?usp=sharing)


[Back to the top](#msc-computing-project)


## Software artefact: AI Governance Regulatory Spectrum

## Overview

This MSc project examines how EU and US artificial intelligence governance documents position themselves across a regulatory spectrum. The project develops a reproducible NLP-based artefact that analyses selected legislative, policy and strategic documents and maps them across two axes:

- **X-axis:** rights- and citizen-oriented safeguards ↔ innovation
- **Y-axis:** voluntary/soft-law ↔ mandatory/control

The artefact uses dictionary-based NLP techniques, PDF text extraction, tokenisation, lemmatisation, predefined analytical vocabularies and document-level legal-force multipliers.


## AI Governance Regulatory Spectrum 

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

The full reproducible artefact is available here:

[AI Governance Regulatory Spectrum Artefact v1.3](https://github.com/narchondas/ai-governance-regulatory-spectrum-v1-3)


## Open in Colab

[Open the replication notebook in Google Colab](https://colab.research.google.com/drive/16RC0ycwxF866B_RKDviYexnJhvZ9ZLsA?usp=sharing)

<img width="409" height="308" alt="image" src="https://github.com/user-attachments/assets/6e7fd09f-0b42-47b2-9733-a43a32896b65" />


## Custom artefact notebook

A custom version of the artefact is also available, allowing researchers to upload different documents and apply the same v1.3 methodology.

Researchers may define their own document groups, such as `Group I` and `Group II`, assign document types and legal-force multipliers, and generate the same categories of outputs.

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

The custom notebook uses the same v1.3 logic. No word-level weights. All terms and phrases count as one occurrence. The document-level legal-force multiplier is applied only to the mandatory/control count. 

This version is therefore intended for reuse and experimentation. It allows researchers to test how other AI-related legal, policy, strategic, institutional or organisational documents are positioned on the same regulatory spectrum.

[AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test](https://github.com/narchondas/custom-ai-governance-regulatory-spectrum-v1-3/blob/main/notebooks/AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test.ipynb)


## Open in Colab

[Open the custom arterfact notebook in Google Colab](https://colab.research.google.com/drive/1Q57pGWiLIeZ95LPFXXLLrJE1m4-lyqtv?usp=sharing)



<img width="458" height="299" alt="image" src="https://github.com/user-attachments/assets/93d2e5f1-98c8-4305-946d-a005268ae0d2" />


## Executive Summary

This research project examines the differing and evolving patterns of artificial intelligence (AI) governance in the European Union (EU) and the United States (US), while demonstrating how reproducible AI-supported text mining can assist the systematic analysis of policy and regulatory documents. It combines a comparative analysis of AI governance instruments with the development of a reproducible analytical artefact designed to identify, measure and visualise differences in regulatory orientation.

The empirical analysis provides evidence of a differentiated EU–US regulatory orientation. Within the corpus examined, EU documents generally exhibit stronger safeguard- and mandatory-oriented characteristics, whereas US documents generally show stronger innovation- and voluntary-oriented characteristics. This distinction should, however, be understood as a dominant pattern rather than a rigid division. Neither jurisdiction is internally uniform. EU governance includes innovation-oriented strategies and voluntary initiatives, while US instruments also contain significant safeguards, risk-management approaches and regulatory elements. The results therefore point to different prevailing institutional and regulatory configurations rather than two completely opposed models of AI governance.

<img width="1350" height="900" alt="newplot (5)" src="https://github.com/user-attachments/assets/cc7c53b6-23fb-4a4c-a12b-29f881e1426b" />

A second important finding is the substantial internal variation within both jurisdictions. Legislation, strategies, guidance, executive instruments and voluntary initiatives occupy different positions within the regulatory landscape. This variation demonstrates the limitations of treating either the EU or the US as a single, homogeneous regulatory model. The findings also indicate that the relationship between innovation, safeguards and legal force is multidimensional. The research therefore employs a two-dimensional analytical model combining innovation versus safeguards with mandatory versus voluntary characteristics. This provides a more informative representation of governance positions than a single linear regulatory spectrum, particularly where instruments display comparable substantive priorities but differ substantially in their degree of legal force.

<img width="1100" height="900" alt="newplot (6)" src="https://github.com/user-attachments/assets/0ee9cb56-0d24-4edb-bba2-6fa8d939bf59" />

The research also identifies elements of convergence alongside divergence. EU and US AI governance cannot be understood simply as opposing regulatory trajectories. Both increasingly address innovation, safeguards, security, competitiveness and responsible AI, although these priorities are articulated and implemented through different institutional arrangements and regulatory instruments. The resulting picture is therefore one of differentiated governance with areas of substantive convergence rather than complete regulatory separation.

<img width="1300" height="750" alt="newplot (7)" src="https://github.com/user-attachments/assets/038671e3-e8b7-49a0-8bb0-d276e1a3db52" />

The methodological contribution complements these substantive findings. The research artefact applies structured text-mining techniques to a defined policy corpus, converting textual patterns into comparable frequencies, analytical scores and visualisations. The results demonstrate the potential of reproducible NLP-based analysis to support the systematic comparison of policy documents and to make complex regulatory patterns more visible. The artefact is consequently best understood as a reproducible analytical tool and proof of concept for supporting comparative policy analysis, rather than as an autonomous or definitive classification system. Its value lies in supporting systematic comparison and generating evidence that can subsequently be examined and interpreted by researchers and policy analysts.

<img width="1350" height="750" alt="newplot (19)" src="https://github.com/user-attachments/assets/e0892d49-5bea-4848-85c1-6a7412d9ede7" />

The documentary and computational findings were further contextualised through expert interviews. Their contribution was not to replace the empirical analysis, but to test and interpret the patterns identified through the documentary corpus and the artefact. The triangulation reinforces the interpretation that differences in AI governance reflect not only regulatory choices but also broader institutional, economic and policy environments. At the same time, the interviews underline the importance of avoiding overly simplified explanations of EU–US differences, particularly where questions of innovation, competitiveness, investment and regulatory capacity interrelate.

<img width="1100" height="800" alt="newplot (28)" src="https://github.com/user-attachments/assets/d454f64b-2733-43e4-adc0-2be4e1e3a73c" />

The findings should nevertheless be interpreted in light of several limitations. The results are dependent on the composition of the selected corpus, the rapidly evolving nature of AI governance, and the vocabulary and weighting choices underlying the text-mining approach. Automated text analysis can identify systematic textual patterns, but it cannot independently establish the full legal, institutional or political meaning of a document. Human validation and interpretation therefore remain essential. These limitations reinforce rather than undermine the role of the artefact as an analytical aid and establish appropriate boundaries for its use.

<img width="1350" height="750" alt="newplot (19)" src="https://github.com/user-attachments/assets/36fae006-81b6-425a-b73e-12b6ad261ca0" />

Overall, the research makes a combined substantive and methodological contribution. Substantively, it provides empirical evidence for differentiated EU and US AI governance orientations while demonstrating the internal diversity and partial convergence that characterise both regulatory environments. Methodologically, it develops a reproducible framework for transforming policy text into structured evidence that can be compared and visualised systematically. The research thus demonstrates how computational text analysis can complement established qualitative and documentary approaches to policy research, while retaining human interpretation at the centre of the analytical process.

<img width="1400" height="800" alt="newplot (11)" src="https://github.com/user-attachments/assets/e2cff0b3-9546-48e2-84b4-50e5cb28a81d" />


## Artefact presentation

Below is the presentation of the AI-supported text-mining artefact developed as part of the thesis. It provides an overview of the artefact, its analytical framework, workflow, methodology and principal outputs.

The presentation is intended to provide researchers with a concise introduction to the artefact and its potential use as a reproducible analytical tool for comparative policy analysis.

[View the Artefact Presentation](https://docs.google.com/presentation/d/1dNavA1vlAsvzpH2fEvJHkAzDGdFYxkX-42Bc9e9Ew3I/edit?usp=sharing)

[Back to the top](#msc-computing-project)



[Go to main Menu](https://narchondas.github.io/)

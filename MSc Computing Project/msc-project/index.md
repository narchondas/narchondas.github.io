# MSc Computing Project

This is my learning experience from Module 7 of the MSc Artificial Intelligence

<img width="203" height="105" alt="image" src="https://github.com/user-attachments/assets/6f0efbe0-c118-4e22-ad25-283c350627b4" />


Use the following links to navigate to the start of the sections

[1. Learning Outcomes](#learning-outcomes)

[2. Project Title and Research Proposal](#project-title-and-research-proposal)

[3. Software artefact: AI Governance Regulatory Spectrum](#software-artefact-AI-governance-regulatory-spectrum-artefact)


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


[Back to the top](#MSc-computing-project)


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


[Back to the top](#MSc-computing-project)


## Software artefact: AI Governance Regulatory Spectrum


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

<img width="409" height="308" alt="image" src="https://github.com/user-attachments/assets/6e7fd09f-0b42-47b2-9733-a43a32896b65" />


## Custom artefact notebook

In addition to the replication notebook, a custom version of the artefact is also available.

The replication notebook reproduces the thesis results using the same 24 public AI governance documents. By contrast, the custom notebook allows another researcher to upload different documents and apply the same v1.3 methodology.

Researchers may define their own document groups, such as `Group I` and `Group II`, assign document types and legal-force multipliers, and generate the same categories of outputs, including the regulatory spectrum graph, four-component profile, heatmap, quadrant distribution, driver terms, slope chart, document-type comparison and vocabulary audit tables.

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

[AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test](https://github.com/narchondas/custom-ai-governance-regulatory-spectrum-v1-3/blob/main/notebooks/AI_Governance_Regulatory_Spectrum_Artefact_v1_3_Custom_Test.ipynb)


## Open in Colab

[Open the custom arterfact notebook in Google Colab](https://colab.research.google.com/drive/1Q57pGWiLIeZ95LPFXXLLrJE1m4-lyqtv?usp=sharing)


## Status

This page forms part of my MSc learning path and presents the artefact developed for my thesis in Artificial Intelligence.

<img width="458" height="299" alt="image" src="https://github.com/user-attachments/assets/93d2e5f1-98c8-4305-946d-a005268ae0d2" />



[Back to the top](#MSc-computing-project)



[Go to main Menu](https://narchondas.github.io/)

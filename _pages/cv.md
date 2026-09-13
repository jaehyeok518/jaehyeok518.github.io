---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/JaeHyeok_Han_CV.pdf" class="btn btn--primary" download><i class="fas fa-download"></i> Download CV (PDF)</a>

Education
======
* B.S. in Biomedical Software, The Catholic University of Korea, Mar. 2025 – Present (GPA: 4.22 / 4.50)

Research interests
======
* Clinical AI, Electronic Health Records, Robustness and Transportability, Clinical Natural Language Processing, Large Language Models

Research experience
======
* Undergraduate Researcher, The Catholic University of Korea (Nov. 2025 – Present)
  * Advisor: Prof. Hyo Jung Kim
  * **Information-Channel Decomposition in Electronic Health Records** — investigating how observation patterns, recorded values, and static patient information contribute to clinical prediction using MIMIC-IV and eICU.
  * **Transportability of HPV Risk Prediction Models** — studying model transportability from NHANES to multinational DHS populations under limited covariate overlap and label-free target settings.
  * **Clinical Text Inference with Large Language Models** — evaluating LLMs for clinical concept detection, encounter-status inference, and negation recognition.
  * **Incisional Hernia Outcomes Using National Claims Data** — cohort definition, exploratory analysis, subgroup design, and statistical analysis using Korean national claims data.
  * **Breast Cancer Subtype Classification from Pathology Reports** — comparative NLP and LLM experiments for subtype classification using IHC pathology reports.
  * **FAERS Data Preprocessing for Pharmacovigilance Research** — preprocessing and deduplication of FDA Adverse Event Reporting System data.

Skills
======
* **Programming:** Python, C++, R, SQL
* **Deep Learning:** PyTorch, scikit-learn
* **Data Analysis:** pandas, NumPy, Matplotlib
* **Tools:** Git, Linux, PostgreSQL

Publications & submissions
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Certifications and languages
======
* **Certifications:** SQL Developer (SQLD), ADsP
* **English:** TOEIC 950 / 990

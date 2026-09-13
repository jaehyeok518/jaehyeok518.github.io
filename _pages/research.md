---
permalink: /research/
title: "Research"
author_profile: true
---

I am an undergraduate researcher at The Catholic University of Korea, advised by Prof. Hyo Jung Kim.
My work centers on **clinical machine learning**, **electronic health records (EHR)**, and **clinical
natural language processing**, with a recurring interest in whether prediction models stay reliable when
they are moved to new populations and settings. Below are the projects I am involved in.

Information-Channel Decomposition in Electronic Health Records
======
Investigating how three distinct information channels — *observation patterns* (what gets measured and when),
*recorded values*, and *static patient information* — each contribute to clinical prediction. The goal is to
understand which signals drive model performance rather than treating the EHR as one undifferentiated input.
*Data: MIMIC-IV, eICU.* Related submission: [KOSMI 2026](/publications/).

Transportability of HPV Risk Prediction Models
======
Studying how risk prediction models transport from a source population (NHANES) to multinational target
populations (DHS) under **limited covariate overlap** and **label-free target settings**, together with
positivity diagnostics for when such transport is justified. *Data: NHANES → DHS.* Related submission:
[KOSMI 2026](/publications/).

Clinical Text Inference with Large Language Models
======
Evaluating large language models for clinical text understanding — **clinical concept detection**,
**encounter-status inference**, and **negation recognition** — to assess where LLMs are dependable for
extracting structured meaning from unstructured notes.

Incisional Hernia Outcomes Using National Claims Data
======
Contributing to a claims-based outcomes study: cohort definition, exploratory analysis, subgroup design,
and statistical analysis. *Data: Korean national claims data.*

Breast Cancer Subtype Classification from Pathology Reports
======
Comparative NLP and LLM experiments for classifying breast cancer subtypes from **immunohistochemistry (IHC)
pathology reports**, comparing traditional NLP pipelines against LLM-based approaches.

FAERS Data Preprocessing for Pharmacovigilance
======
Preprocessing and **deduplication** of the FDA Adverse Event Reporting System (FAERS) data to build a clean
foundation for downstream pharmacovigilance analysis.

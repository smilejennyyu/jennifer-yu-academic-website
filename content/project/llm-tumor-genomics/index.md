---
title: "Generalist Large Language Models for Tumor Genomics Interpretation"
summary: Benchmarking zero-shot large language models against supervised, tailor-made predictors on cancer-type, somatic-vs-CHIP and variant-oncogenicity classification across 100,000+ samples from 19 institutions, and combining them into LLM–specialist ensembles that raise cross-institution accuracy by up to 55%.

tags:
  - Large Language Models
  - Precision Oncology
  - Ongoing
date: '2025-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: "Generalist large language models applied to AACR Project GENIE tumor-genomic profiles to separate clonal hematopoiesis from tumor-derived variants, classify variant oncogenicity, and predict cancer type."
  focal_point: Smart

links:
  - name: AACR 2026 abstract
    url: /publication/conference-paper/aacr2026-llm/
url_code: 'https://github.com/smilejennyyu/llm_cancer_type_classification'
url_pdf: 'https://www.biorxiv.org/content/10.64898/2026.05.21.726957v1.full.pdf'
url_slides: ''
url_video: ''
---

Tumor genomic profiling produces results that must be interpreted before they can guide care: what is the most likely cancer type, is a variant somatic or the result of clonal hematopoiesis (CHIP), and is it likely to be oncogenic? Specialized, tailor-made predictors exist for each of these questions, but they are trained on a single institution's data and labels and can degrade when deployed elsewhere.

In this project, which I lead as part of my PhD work with Dr. Quaid Morris and Dr. Justin Jee at Memorial Sloan Kettering Cancer Center, we benchmark zero-shot generalist large language models against supervised baselines on cancer-type, somatic-vs-CHIP and variant-oncogenicity classification using more than 100,000 samples from 19 institutions. We find that generalist LLMs and tailor-made predictors are complementary: LLM–specialist ensembles raise cross-institution accuracy by up to 55%. The work was presented at the AACR Annual Meeting 2026 and ISMB 2026, and a preprint is available on bioRxiv.

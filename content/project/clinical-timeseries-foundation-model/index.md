---
title: "Foundation Models for Longitudinal Clinical Time Series in Oncology"
summary: SPARC, a transformer-based foundation model pretrained on more than 100 million longitudinal laboratory and vital-sign measurements from 224,047 patients with cancer, used to predict treatment toxicities, adverse events and mortality.

tags:
  - Time Series
  - Precision Oncology
  - Ongoing
date: '2024-09-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: "SPARC architecture: real-world EHR laboratory and vital-sign time series are grouped into clinical modules, encoded with module-wise and time embeddings, pretrained autoregressively, and fine-tuned to predict mortality and medication side effects."
  focal_point: Smart

links:
url_code: 'https://github.com/tommyfuu/SPARC'
url_pdf: 'https://www.medrxiv.org/content/10.64898/2026.10.22.26364879.full.pdf'
url_slides: ''
url_video: ''
---

Routine clinical care generates long, irregular time series of laboratory values and vital signs for every patient. For patients with cancer, these measurements carry early signals of treatment toxicities and other adverse events, but they are rarely modeled jointly and longitudinally.

As part of my PhD work with Dr. Quaid Morris and Dr. Justin Jee at Memorial Sloan Kettering Cancer Center, I contribute to SPARC, a transformer-based foundation model pretrained on more than 100 million longitudinal lab and vital-sign measurements from 224,047 patients with cancer. The pretrained model is fine-tuned to predict treatment toxicities, adverse events and mortality, and generalizes to external cancer centers. The project was presented at the NeurIPS 2025 Workshop on Learning from Time Series for Health (TS4H) and at ISMB 2026, where it received a Best Oral Presentation award; a preprint, *Longitudinal AI Models Predict Cancer Adverse Events*, is available on medRxiv.

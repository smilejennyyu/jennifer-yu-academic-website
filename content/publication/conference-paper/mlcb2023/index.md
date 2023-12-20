---
title: 'A Multi-Granularity Approach to Similarity Search in Multiplexed Immunofluorescence Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhenqin Wu
  - Aaron Mayer
  - Alexandro Trevino
  - James Zou

# Author notes (optional)
author_notes:
  - 'Presenter'

date: '2023-12-19T00:00:00Z'
doi: '10.1101/2023.11.26.568745'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-19T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 18th Machine Learning in Computational Biology*
publication_short: In *MLCB 2023*

abstract: Due to the rapid increase and importance of multiplexed immunofluorescence (mIF) imaging data in spatial biology, there is a pressing need to develop efficient image-to-image search pipelines for both diagnostic and research purposes. While several image search methods have been introduced for conventional images and digital pathology, mIF images present three main challenges:\ (1) high dimensionality, (2) domain-specificity, and (3) complex additional molecular information. To address this gap, we introduce the MIISS framework, a Multi-granularity mIF Image Similarity Search pipeline that employs self-supervised learning models to extract features from mIF image patches and an entropy-based aggregation method to enable similarity searches at higher, multi-granular levels. We then benchmarked various feature generation approaches to handle high dimensional images and tested them on various foundation models. We conducted evaluations using datasets from different tissues on both patch- and patient-level, which demonstrate the framework's effectiveness and generalizability. Notably, we found that domain-specific models consistently outperformed other models, further showing their robustness and generalizability across different datasets. The MIISS framework offers an effective solution for navigating the growing landscape of mIF images, providing tangible clinical benefits and opening new avenues for pathology research.

# Summary. An optional shortened abstract.
summary: First image similarity search system on multiplexed immunofluorescence (mIF) tissue images

tags: [Change point detection, Time series, Dynamic window, Health monitoring]

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://www.biorxiv.org/content/10.1101/2023.11.26.568745v1.full.pdf'
url_poster: 'publication/conference-paper/mlcb2023/MLCB2023_poster.pdf'

---



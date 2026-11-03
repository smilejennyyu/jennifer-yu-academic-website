---
title: 'Generalist large language models complement tailor-made predictors for tumor genomics interpretation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Madison Darmofal
  - Michele Waters
  - January Choy
  - Thinh N. Tran
  - Chenlian Fu
  - Leah Morales
  - Kaicheng U
  - Ross L. Levine
  - Nikolaus Schultz
  - Michael F. Berger
  - Quaid Morris
  - Justin Jee

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding author'
  - 'Corresponding author'

date: '2026-05-22T00:00:00Z'
doi: '10.64898/2026.05.21.726957'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 'Preprint on *bioRxiv* (under review at *Nature Communications*)'
publication_short: '*bioRxiv*'

abstract: "General-purpose large language models (LLMs) are trained on large corpora to acquire broad knowledge, but whether LLMs can replace, or augment, task-specific models is unclear. We evaluated LLMs on three real-world, clinically important tumor genomic interpretation tasks, in order of increasing difficulty: (i) distinguishing tumor from non-tumor mutations (n=34,415 variants), (ii) distinguishing driver from passenger mutations (n=13,469 variants), and (iii) inferring cancer type from tumor sequencing reports across multiple assays and institutions (n=102,791 samples). The best general-purpose LLMs performed as well as the benchmark tailor-made predictor for task (i). Ensembling tailor-made models with zero-shot LLMs improved their performance for tasks (i) and (ii). For task (iii), LLMs outperformed or supplemented tailor-made models on out-of-distribution data. Without fine-tuning, current LLMs already can be useful in clinical genomic interpretation by adding complementary expertise to tailor-made, state-of-the-art predictors."


# Summary. An optional shortened abstract.
summary: General-purpose large language models, used without any fine-tuning, match or complement specialized predictors on three tumor genomic interpretation tasks, with the largest gains on data from new assays and institutions.

tags: [Large Language Models, Precision Oncology, Cancer Genomics, Machine Learning]

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://www.biorxiv.org/content/10.64898/2026.05.21.726957v1.full.pdf'
url_code: 'https://github.com/smilejennyyu/llm_cancer_type_classification'

---

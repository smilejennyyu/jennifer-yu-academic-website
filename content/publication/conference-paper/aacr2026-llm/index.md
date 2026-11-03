---
title: 'Large language models for tumor genomic interpretation'

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

date: '2026-04-03T00:00:00Z'
doi: '10.1158/1538-7445.AM2026-4100'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "Abstract in *Cancer Research* 86(7_Supplement): 4100 — *AACR Annual Meeting 2026*"
publication_short: In *AACR 2026*

abstract: |-
  Introduction: Algorithms trained on real-world data aid in tumor genomic prediction tasks, such as identifying cancer driver mutations and inferring cancer type. The extent to which generalist large language models (LLMs) trained on large natural language corpora can replace or supplement such domain-specific algorithms with zero-shot inference is unknown.
  Methods: We evaluated the zero-shot performance of proprietary (GPT-5, o3-mini, GPT-4o and Claude 3.7 Sonnet), open weight (DeepSeek and Qwen3) and domain-specialized medical (MedGemma) LLMs on three tasks: (i) Distinguishing tumor-somatic mutations from clonal hematopoietic (CH) variants in patients with matched tumor-whole blood profiling (N=37,179 patients; 54,807 samples), (ii) Classifying oncogenic variants using the OncoKB dataset as a positive control (N=10,489 patients; 10,752 samples; 13,470 variants), and (iii) Predicting cancer type from tumor genomic profiles in the multi-institution AACR GENIE dataset (N=97,074 patients; 102,791 samples).
  Results: Multiple LLMs approached the accuracy of MetaCH, a supervised model for distinguishing somatic tumor mutations from CH variants. o3-mini achieved the highest accuracy for distinguishing oncogenic driver from benign passenger mutations. Among patients with non-small cell lung cancer and mutations in KEAP1, those with VUSs classified as oncogenic by GPT-5 had worse overall survival than those with VUSs classified as benign. GPT-5, o3-mini, and Claude 3.7 Sonnet had accuracy approaching that of a supervised model, GDD-ENS, at classifying 34 cancer types using tumor genomic profiles. Ensemble approaches combining prediction results from GPT-5 and GDD-ENS improved cross-institutional generalizability and performance by an average of 20%. In their reasoning, LLMs discussed clinically relevant genomic features consistent with feature importances from GDD-ENS.
  Conclusion: Without task-specific training, LLMs achieved performance comparable to specialized supervised models across all tasks.

# Summary. An optional shortened abstract.
summary: Without any task-specific training, general-purpose large language models approach the accuracy of specialized supervised models at separating tumor mutations from clonal hematopoiesis variants, flagging oncogenic variants and predicting cancer type from tumor genomic profiles, and ensembling them with a supervised classifier improves generalization across institutions.

tags: [Large Language Models, Precision Oncology, Cancer Genomics, Machine Learning]

# Display this page in the Featured widget?
featured: false

url_code: 'https://github.com/smilejennyyu/llm_cancer_type_classification'

---

Also presented at ISMB 2026.

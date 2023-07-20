---
title: "Learning Limited: How limited data sharing impacts machine learning performance in health"
summary: This study finds that machine learning models trained on pooled electronic health record (EHR) data from multiple sites can generalize better to unseen data, while also revealing that data sharing partnerships may not always enhance performance, and certain baseline models continue to be competitive except in few-shot learning scenarios.


tags:
  - Time Series
  - Ongoing
date: '2023-04-19T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Electronic health records (EHR) are filled with sensitive information, such as comorbidities and prescriptions, that can be leveraged by machine learning to improve patient care. However, limitations on data sharing have relegated the machine learning for health community to develop models on private local data, or a handful of publicly released datasets. Therefore, the portability of machine learning training approaches across several EHRs has yet to be thoroughly explored. To fill this gap, we illustrate model performance in situations in which EHRs may be shared.

In a broad set of experiments, we find that models trained across data pooled from several sites can indeed generalise to unseen in-domain data better than single domain training, regardless of their encoding. Pooled learning with local encoders, having data from all sources available simultaneously at training time, has the added benefit that the uniquely structured EHRs do not need to be mapped to an interoperable format when site-specific encoders are learned in a supervised fashion.

Further, if institutions seek to form data sharing partnerships instead of housing their data in shared data repositories, they may find less benefit. We also find that roughly a quarter of the data partnerships formed are not helpful to either site for classification performance, while half of them are beneficial to both sites. Interestingly, a quarter of them are only unilaterally helpful and site similarity alone does not imply transferability. The beneficial relationships were not observed for large supervised dataset classification tasks, however.

Additionally, when EHRs are mapped to a common format, zero-shot models fail to reach fully-labelled single-institution performance. In this case, fine-tuning can exceed single-institution performance with substantially fewer patients. Baseline models like XGBoost remained competitive, except for in the few-shot learning challenge; Even when none of the positive labels are in the fine-tuning samples neural architectures see consistent improvements over zero-shot models.

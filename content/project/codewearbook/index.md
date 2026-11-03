---
title: "CodeWearBook: Agentic Natural-Language Querying of Wearable Health Datasets"
summary: Retrieval-grounded LLM agents that let researchers query large wearable health datasets in natural language, with privacy preserved by restricting the model to controlled SQL and Python execution layers instead of raw data access.

tags:
  - Large Language Models
  - Time Series
  - NLP
date: '2024-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: "Overview of the CodeWearBook workflow: dataset-scope selection and query disambiguation, embedding-based schema and knowledge retrieval, and SQL generation with majority voting and execution."
  focal_point: Smart

links:
  - name: Manuscript (under review)
    url: /publication/preprint/codewearbook/
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

Longitudinal wearable studies such as those run by the Goldenberg Lab in collaboration with [4YouandMe](https://4youandme.org/) produce large, heterogeneous datasets of physiological signals, surveys and clinical events. Asking even simple questions of these data usually requires a data engineer and custom code.

CodeWearBook is an agentic workflow, developed with Dr. Anna Goldenberg's group at the University of Toronto, the Vector Institute and SickKids, in which large language models answer natural-language questions about wearable health datasets by generating and executing code. The workflow is designed to be adaptable to new data sources and contexts while ensuring data privacy and security by restricting the LLM's access to raw participant data through controlled SQL and Python execution layers. A manuscript describing the system is under review.

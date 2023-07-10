---
title: 'Extending Similarity Network-Based Classifiers to the Non-Coding Genome and Deep Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Duncan Forster
  - Shraddha Pai

# Author notes (optional)
author_notes:
  - 'Presenter'

date: '2021-11-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Machine Learning in Computational Biology 2021*
publication_short: In *MLCB 2021*

abstract: Similarity networks provide a useful framework for multi-modal data integration, suitable for applications such as gene function prediction and patient classification. We previously developed a supervised learning algorithm which converted heterogeneous patient data into the common space of patient similarity networks (PSN) and used these networks as input features2 (netDx.org). In addition to excellent classification performance and handling missing data, netDx provides interpretability by allowing users to group genes into pathway-level features. However, the pathway-based grouping approach is of limited value for genomic data outside coding regions. Moreover, the current framework has limited scalability in the number of nodes and networks and does not take advantage of improved discriminability available in the deep learning framework. Here, we describe two recent areas of work addressing these limitations. In the first, we classify binary survival in PFA ependymomas using tumour DNA methylomes organized with prior knowledge of brain tissue- and cell-specific expression, transcription factor binding sites and chromatin state. In the second, we extend a recently developed framework called BIONIC for multiple network integration based on graph convolutional networks, to classification. Developing an approach to score features for interpretability remains an active area of research.

# Summary. An optional shortened abstract.
summary: Based on the idea of patient similarity network, we extended a graph convolutional network framework to classifiy clinical outcomes of cancer patients.

tags: [Multi-modal Data Integration, Graph Neural Network, Precision Medicine, Deep Learning, Machine Learning]

# Display this page in the Featured widget?
featured: false

url_pdf: 'publication/conference-paper/mlcb2021/MLCB2021_abstract.pdf'
url_code: 'https://github.com/RealPaiLab/BIONIC'
url_poster: 'publication/conference-paper/mlcb2021/MLCB2021_poster.pdf'

---



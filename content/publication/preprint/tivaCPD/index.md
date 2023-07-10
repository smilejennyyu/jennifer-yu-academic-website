---
title: "Dynamic Interpretable Change Point Detection"
authors:
- admin
- Kopal Garg
- Tina Behrouzi
- Sana Tonekaboni
- Anna Goldenberg

# Author notes (optional)
author_notes:
  - 'Equal contributor'
  - 'Equal contributor'
  - 'Equal contributor'

date: "2023-06-07T00:00:00Z"
doi: "10.48550/arXiv.2211.03991"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: Identifying change points (CPs) in a time series is crucial to guide better decision making across various fields like finance and healthcare and facilitating timely responses to potential risks or opportunities. Existing Change Point Detection (CPD) methods have a limitation in tracking changes in the joint distribution of multidimensional features. In addition, they fail to generalize effectively within the same time series as different types of CPs may require different detection methods. As the volume of multidimensional time series continues to grow, capturing various types of complex CPs such as changes in the correlation structure of the time-series features has become essential. To overcome the limitations of existing methods, we propose TiVaCPD, an approach that uses a Time-Varying Graphical Lasso (TVGL) to identify changes in correlation patterns between multidimensional features over time, and combines that with an aggregate Kernel Maximum Mean Discrepancy (MMD) test to identify changes in the underlying statistical distributions of dynamic time windows with varying length. The MMD and TVGL scores are combined using a novel ensemble method based on similarity measures leveraging the power of both statistical tests. We evaluate the performance of TiVaCPD in identifying and characterizing various types of CPs and show that our method outperforms current state-of-the-art methods in real-world CPD datasets. We further demonstrate that TiVaCPD scores characterize the type of CPs and facilitate interpretation of change dynamics, offering insights into real-life applications.


# Summary. An optional shortened abstract.
summary: We developed a novel and interpretable change point detection method that utilize both Time-Varying Graphical Lasso (TVGL) approach and Maximum Mean Discrepancy (MMD) tests.

tags: [Change Point Detection, Time Series Analysis, Kernel Methods, Machine Learning]

featured: false

links:
url_pdf: https://arxiv.org/pdf/2211.03991.pdf
url_code: 'https://github.com/smilejennyyu/TiVaCPD'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

---
title: 'Dynamic Interpretable Change Point Detection for Physiological Data Analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tina Behrouzi
  - Kopal Garg
  - Anna Goldenberg 
  - Sana Tonekaboni

# Author notes (optional)
author_notes:
  - 'Presenter'

date: '2023-12-10T00:00:00Z'
doi: '10.48550/arXiv.2211.03991'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 3rd Machine Learning for Health*
publication_short: In *ML4H 2023*

abstract: Identifying change points (CPs) in time series is crucial to guide better decision-making in healthcare, and facilitating timely responses to potential risks or opportunities. In maternal health, monitoring health signals in pregnant women allows healthcare providers to promptly respond to complications like preeclampsia or enhance delivery time detection, improving overall maternal care. Existing Change Point Detection (CPD) methods often fail to generalize effectively due to diverse underlying changes that can cause a CP. We propose Ti me Va rying CPD (TiVaCPD), a change point detection method that captures different types of changes in the underlying distribution of multidimensional data. It combines a dynamic window MMD test with a graphical Lasso estimator of feature covariance to measure both changes in the joint distribution of the observations as well as changes in feature dynamics. TiVaCPD generates a unifying CP score by evaluating the relative similarity of the statistical tests. Additionally, TiVaCPD score enhances interpretability by offering insight into the underlying causes of CPs through a detailed analysis of feature dynamics, which is especially valuable in healthcare applications. We evaluate the performance of TiVaCPD on both simulated and real-world data, showing that it can outperform state-of-the-art methods. We further demonstrate the appliance of TiVaCPD in a pregnancy-related case study, showcasing the joint shifts in physiological signals that facilitate the detection of delivery time.


# Summary. An optional shortened abstract.
summary: Interpretable change point detection method

tags: [Change point detection, Time series, Dynamic window, Health monitoring]

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://proceedings.mlr.press/v225/yu23a/yu23a.pdf'
url_code: 'https://github.com/smilejennyyu/TiVaCPD'
url_poster: 'publication/conference-paper/ml4h2023/TiVaCPD_poster.pdf'

---



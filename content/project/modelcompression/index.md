---
title: Model Compression
summary: This project focuses on memory compression techniques for image compression algorithms due to the high cost of transferring data and computation between different units.

tags:
  - Model Compression
date: '2023-04-13T00:00:00Z'

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
url_code: 'https://github.com/smilejennyyu/csc2231-image-compression'
url_pdf: 'project/modelcompression/report.pdf'
url_poster: 'project/modelcompression/poster.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

  Image compression is crucial as images continue to increase in number due to advancements in computing power and mobile camera capabilities. To save space and transfer images more quickly, it is necessary to reduce the size of digital images while maintaining their necessary information. Deep Neural Networks (DNNs) have become powerful tools for various computer vision tasks, including image compression. However, DNNs are computationally intensive, requiring acceleration techniques to meet increasing needs. These techniques can be categorized into three categories: memory compression, computational optimization, and dataflow optimization. Model compression falls under the category of memory compression and the goal is to achieve a model that is simplified from the original without significantly diminishing accuracy and with a reduction in size and/or latency from the original. This project focuses on model compression techniques, such as pruning and quantization, on image compression algorithms to compare the performance of the compressed models to the original models. Our results show that pruning has different effects when applying to different components of the image compression models.

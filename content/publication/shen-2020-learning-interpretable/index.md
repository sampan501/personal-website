---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Interpretable Characteristic Kernels via Decision Forests
subtitle: ''
summary: ''
authors:
- Cencheng Shen
- admin
- Joshua T. Vogelstein
tags: []
categories: []
date: '2020-09-01'
lastmod: 2022-11-25T11:05:01-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ['hyppo', 'rf']
publishDate: '2022-11-25T16:05:01.214577Z'
publication_types:
- '3'
abstract: Decision forests are popular tools for classification and regression. These
  forests naturally produce proximity matrices measuring how often each pair of observations
  lies in the same leaf node. It has been demonstrated that these proximity matrices
  can be thought of as kernels, connecting the decision forest literature to the extensive
  kernel machine literature. While other kernels are known to have strong theoretical
  properties such as being characteristic, no similar result is available for any
  decision forest based kernel. In this manuscript,we prove that the decision forest
  induced proximity can be made characteristic, which can be used to yield a universally
  consistent statistic for testing independence. We demonstrate the performance of
  the induced kernel on a suite of 20 high-dimensional independence test settings.
  We also show how this learning kernel offers insights into relative feature importance.
  The decision forest induced kernel typically achieves substantially higher testing
  power than existing popular methods in statistical tests.

links:
url_pdf: https://arxiv.org/abs/1812.00029.pdf
url_code: 'https://hyppo.neurodata.io/api/generated/hyppo.independence.kmerf#hyppo.independence.KMERF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/neurodata/hyppo-papers/tree/main/kmerf'
url_video: ''
---

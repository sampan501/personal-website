---
# Documentation: https://wowchemy.com/docs/managing-content/

title: When Are Deep Networks Really Better than Decision Forests at Small Sample
  Sizes, and How?
subtitle: ''
summary: ''
authors:
- Haoyin Xu
- Kaleab A. Kinfu
- Will LeVine
- admin
- Jayanta Dey
- Michael Ainsworth
- Yu-Chung Peng
- Madi Kusmanov
- Florian Engert
- Christopher M. White
- Joshua T. Vogelstein
- Carey E. Priebe
tags: []
categories: []
date: '2021-11-01'
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
projects: ['rf']
publishDate: '2022-11-25T16:05:01.793162Z'
publication_types:
- '3'
abstract: Deep networks and decision forests (such as random forests and gradient
  boosted trees) are the leading machine learning methods for structured and tabular
  data, respectively. Many papers have empirically compared large numbers of classifiers
  on one or two different domains (e.g., on 100 different tabular data settings).
  However, a careful conceptual and empirical comparison of these two strategies using
  the most contemporary best practices has yet to be performed. Conceptually, we illustrate
  that both can be profitably viewed as \"partition and vote\" schemes. Specifically,
  the representation space that they both learn is a partitioning of feature space
  into a union of convex polytopes. For inference, each decides on the basis of votes
  from the activated nodes. This formulation allows for a unified basic understanding
  of the relationship between these methods. Empirically, we compare these two strategies
  on hundreds of tabular data settings, as well as several vision and auditory settings.
  Our focus is on datasets with at most 10,000 samples, which represent a large fraction
  of scientific and biomedical datasets. In general, we found forests to excel at
  tabular and structured data (vision and audition) with small sample sizes, whereas
  deep nets performed better on structured data with larger sample sizes. This suggests
  that further gains in both scenarios may be realized via further combining aspects
  of forests and networks. We will continue revising this technical report in the
  coming months with updated results.

links:
url_pdf: https://arxiv.org/abs/2108.13637.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

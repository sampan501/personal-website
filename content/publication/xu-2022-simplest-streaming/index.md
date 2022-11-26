---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Simplest Streaming Trees
subtitle: ''
summary: ''
authors:
- Haoyin Xu
- Jayanta Dey
- admin
- Joshua T. Vogelstein
tags: []
categories: []
date: '2022-03-01'
lastmod: 2022-11-25T11:05:02-05:00
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
publishDate: '2022-11-25T16:05:01.976961Z'
publication_types:
- '3'
abstract: 'Decision forests, including random forests and gradient boosting trees,
  remain the leading machine learning methods for many real-world data problems, specifically
  on tabular data. However, current standard implementations only operate in batch
  mode, and therefore cannot incrementally update when more data arrive. Several previous
  works developed streaming trees and ensembles to overcome this limitation. Nonetheless,
  we found that those state-of-the-art algorithms suffer from a number of drawbacks,
  including performing very poorly on some problems and requiring a huge amount of
  memory on others. We therefore developed the simplest possible extension of decision
  trees we could think of: given new data, simply update existing trees by continuing
  to grow them, and replace some old trees with new ones to control the total number
  of trees. On three standard datasets, we illustrate that our approach, Stream Decision
  Forest (SDF), does not suffer from either of the aforementioned limitations. In
  a benchmark suite containing 72 classification problems (the OpenML-CC18 data suite),
  we illustrate that our approach often performs as well, and sometimes better even,
  than the batch mode decision forest algorithm. Thus, we believe SDFs establish a
  simple standard for streaming trees and forests that could readily be applied to
  many real-world problems, including those with distribution drift and continual
  learning.'

links:
url_pdf: https://arxiv.org/abs/2110.08483.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

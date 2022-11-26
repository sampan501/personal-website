---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The Chi-Square Test of Distance Correlation
subtitle: ''
summary: ''
authors:
- Cencheng Shen
- admin
- Joshua T. Vogelstein
tags: []
categories: []
date: '2022-01-01'
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
projects: ['hyppo']
publishDate: '2022-11-25T16:05:01.402622Z'
publication_types:
- '2'
abstract: 'Distance correlation has gained much recent attention in the data science
  community: the sample statistic is straightforward to compute and asymptotically
  equals zero if and only if independence, making it an ideal choice to discover any
  type of dependency structure given sufficient sample size. One major bottleneck
  is the testing process: because the null distribution of distance correlation depends
  on the underlying random variables and metric choice, it typically requires a permutation
  test to estimate the null and compute the p-value, which is very costly for large
  amount of data. To overcome the difficulty, in this article, we propose a chi-squared
  test for distance correlation. Method-wise, the chi-squared test is nonparametric,
  extremely fast, and applicable to bias-corrected distance correlation using any
  strong negative type metric or characteristic kernel. The test exhibits a similar
  testing power as the standard permutation test, and can be used for K-sample and
  partial testing. Theory-wise, we show that the underlying chi-squared distribution
  well approximates and dominates the limiting null distribution in upper tail, prove
  the chi-squared test can be valid and universally consistent for testing independence,
  and establish a testing power inequality with respect to the permutation test. Supplementary
  files for this article are available online.'
publication: '*Journal of Computational and Graphical Statistics*'
doi: 10.1080/10618600.2021.1938585

links:
- name: Preprint
  url: https://arxiv.org/abs/1912.12150
url_pdf: https://www.tandfonline.com/doi/pdf/10.1080/10618600.2021.1938585?needAccess=true
url_code: 'https://hyppo.neurodata.io/api/generated/hyppo.independence.dcorr#hyppo.independence.Dcorr.test'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/neurodata/hyppo-papers/tree/main/fast'
url_video: ''
---

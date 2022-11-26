---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Nonpar MANOVA via Independence Testing
subtitle: ''
summary: ''
authors:
- admin
- Cencheng Shen
- Ronan Perry
- Jelle Zorn
- Antoine Lutz
- Carey E. Priebe
- Joshua T. Vogelstein
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: []
categories: []
date: '2021-04-01'
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
publishDate: '2022-11-25T16:05:01.009518Z'
publication_types:
- '3'
abstract: The $k$-sample testing problem tests whether or not $k$ groups of data points
  are sampled from the same distribution. Multivariate analysis of variance (MANOVA)
  is currently the gold standard for $k$-sample testing but makes strong, often inappropriate,
  parametric assumptions. Moreover, independence testing and $k$-sample testing are
  tightly related, and there are many nonparametric multivariate independence tests
  with strong theoretical and empirical properties, including distance correlation
  (Dcorr) and Hilbert-Schmidt-Independence-Criterion (Hsic). We prove that universally
  consistent independence tests achieve universally consistent $k$-sample testing
  and that $k$-sample statistics like Energy and Maximum Mean Discrepancy (MMD) are
  exactly equivalent to Dcorr. Empirically evaluating these tests for $k$-sample scenarios
  demonstrates that these nonparametric independence tests typically outperform MANOVA,
  even for Gaussian distributed settings. Finally, we extend these non-parametric
  $k$-sample testing procedures to perform multiway and multilevel tests. Thus, we
  illustrate the existence of many theoretically motivated and empirically performant
  $k$-sample tests. A Python package with all independence and k-sample tests called
  hyppo is available from https://hyppo.neurodata.io/.

links:
url_pdf: https://arxiv.org/pdf/1910.08883.pdf
url_code: 'https://hyppo.neurodata.io/api/generated/hyppo.ksample.ksample#hyppo.ksample.KSample'
url_dataset: ''
url_poster: '2021-hyppo-brain.pdf'
url_project: ''
url_slides: '2021-hyppo-gyss.pdf'
url_source: 'https://github.com/neurodata/hyppo-papers/tree/main/ksample'
url_video: ''
---

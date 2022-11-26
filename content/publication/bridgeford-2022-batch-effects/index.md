---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Batch Effects Are Causal Effects: Applications in Human Connectomics'
subtitle: ''
summary: ''
authors:
- Eric W. Bridgeford
- Michael Powell
- Gregory Kiar
- Stephanie Noble
- Jaewon Chung
- admin
- Ross Lawrence
- Ting Xu
- Michael Milham
- Brian Caffo
- Joshua T. Vogelstein
tags: []
categories: []
date: '2022-10-01'
lastmod: 2022-11-25T11:05:00-05:00
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
projects: []
publishDate: '2022-11-25T16:05:00.367439Z'
publication_types:
- '3'
abstract: Batch effects, undesirable sources of variance across multiple experiments,
  present a substantial hurdle for scientific and clinical discoveries. Specifically,
  the presence of batch effects can create both spurious discoveries and hide veridical
  signals, contributing to the ongoing reproducibility crisis. Typical approaches
  to dealing with batch effects conceptualize `batches' as an associational effect,
  rather than a causal effect, despite the fact that the sources of variance that
  comprise the batch – potentially including experimental design and population demographics
  – causally impact downstream inferences. We therefore cast batch effects as a causal
  problem rather than an associational problem. This reformulation enables us to make
  explicit the assumptions and limitations of existing approaches for dealing with
  batch effects. We therefore develop causal batch effect strategies – Causal Dcorr
  for discovery of batch effects and Causal ComBat for mitigating batch effects –
  which build upon existing statistical associational methods by incorporating modern
  causal inference techniques. We apply these strategies to a large mega-study of
  human connectomes assembled by the Consortium for Reliability and Reproducibility,
  consisting of 24 batches including over 1700 individuals to illustrate that existing
  approaches create more spurious discoveries (false positives) and miss more veridical
  signals (true positives) than our proposed approaches. Our work therefore introduces
  a conceptual framing, as well as open source code, for combining multiple distinct
  datasets to increase confidence in claims of scientific and clinical discoveries.

links:
url_pdf: https://www.biorxiv.org/content/10.1101/2021.09.03.458920v2.full.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/ebridge2/batch_effects'
url_video: ''
---

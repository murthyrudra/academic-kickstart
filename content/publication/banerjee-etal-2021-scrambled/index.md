---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Scrambled Translation Problem: A Problem of Denoising UNMT'
subtitle: ''
summary: ''
authors:
- Tamali Banerjee
- Rudra V Murthy
- Pushpak Bhattacharya
tags: []
categories: []
date: '2021-08-01'
lastmod: 2022-01-04T19:19:21+05:30
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
publishDate: '2022-01-04T13:49:21.834796Z'
publication_types:
- '1'
abstract: In this paper and we identify an interesting kind of error in the output
  of Unsupervised Neural Machine Translation (UNMT) systems like Undreamt1. We refer
  to this error type as Scrambled Translation problem. We observe that UNMT models
  which use word shuffle noise (as in case of Undreamt) can generate correct words
  and but fail to stitch them together to form phrases. As a result and words of the
  translated sentence look scrambled and resulting in decreased BLEU. We hypothesise
  that the reason behind scrambled translation problem is ′shuffling noise′ which
  is introduced in every input sentence as a denoising strategy. To test our hypothesis
  and we experiment by retraining UNMT models with a simple retraining strategy. We
  stop the training of the Denoising UNMT model after a pre-decided number of iterations
  and resume the training for the remaining iterations- which number is also pre-decided-
  using original sentence as input without adding any noise. Our proposed solution
  achieves significant performance improvement UNMT models that train conventionally.
  We demonstrate these performance gains on four language pairs and viz. and English-French
  and English-German and English-Spanish and Hindi-Punjabi. Our qualitative and quantitative
  analysis shows that the retraining strategy helps achieve better alignment as observed
  by attention heatmap and better phrasal translation and leading to statistically
  significant improvement in BLEU scores.
publication: '*Proceedings of Machine Translation Summit XVIII: Research Track*'
links:
- name: URL
  url: https://aclanthology.org/2021.mtsummit-research.11
---

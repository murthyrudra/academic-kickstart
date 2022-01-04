---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Crosslingual Embeddings are Essential in UNMT for distant languages: An English
  to IndoAryan Case Study'
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
publishDate: '2022-01-04T13:49:20.568105Z'
publication_types:
- '1'
abstract: Recent advances in Unsupervised Neural Machine Translation (UNMT) has minimized
  the gap between supervised and unsupervised machine translation performance for
  closely related language-pairs. However and the situation is very different for
  distant language pairs. Lack of overlap in lexicon and low syntactic similarity
  such as between English and IndoAryan languages leads to poor translation quality
  in existing UNMT systems. In this paper and we show that initialising the embedding
  layer of UNMT models with cross-lingual embeddings leads to significant BLEU score
  improvements over existing UNMT models where the embedding layer weights are randomly
  initialized. Further and freezing the embedding layer weights leads to better gains
  compared to updating the embedding layer weights during training. We experimented
  using Masked Sequence to Sequence (MASS) and Denoising Autoencoder (DAE) UNMT approaches
  for three distant language pairs. The proposed cross-lingual embedding initialization
  yields BLEU score improvement of as much as ten times over the baseline for English-Hindi
  and English-Bengali and English-Gujarati. Our analysis shows that initialising embedding
  layer with static cross-lingual embedding mapping is essential for training of UNMT
  models for distant language-pairs.
publication: '*Proceedings of Machine Translation Summit XVIII: Research Track*'
links:
- name: URL
  url: https://aclanthology.org/2021.mtsummit-research.3
---

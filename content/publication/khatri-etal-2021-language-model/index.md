---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Language Model Pretraining and Transfer Learning for Very Low Resource Languages
subtitle: ''
summary: ''
authors:
- Jyotsana Khatri
- Rudra Murthy
- Pushpak Bhattacharyya
tags: []
categories: []
date: '2021-11-01'
lastmod: 2022-05-13T17:02:14+05:30
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
publishDate: '2022-05-13T11:32:14.177069Z'
publication_types:
- '1'
abstract: 'This paper describes our submission for the shared task on Unsupervised
  MT and Very Low Resource Supervised MT at WMT 2021. We submitted systems for two
  language pairs: German ↔ Upper Sorbian (de ↔ hsb) and German-Lower Sorbian (de ↔
  dsb). For de ↔ hsb, we pretrain our system using MASS (Masked Sequence to Sequence)
  objective and then finetune using iterative back-translation. Final finetunng is
  performed using the parallel data provided for translation objective. For de ↔ dsb,
  no parallel data is provided in the task, we use final de ↔ hsb model as initialization
  of the de ↔ dsb model and train it further using iterative back-translation, using
  the same vocabulary as used in the de ↔ hsb model.'
publication: '*Proceedings of the Sixth Conference on Machine Translation*'
links:
- name: URL
  url: https://aclanthology.org/2021.wmt-1.106
---

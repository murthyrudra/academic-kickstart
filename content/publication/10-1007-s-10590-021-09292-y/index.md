---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Simple Measures of Bridging Lexical Divergence Help Unsupervised Neural Machine
  Translation for Low-Resource Languages
subtitle: ''
summary: ''
authors:
- Jyotsana Khatri
- Rudra Murthy
- Tamali Banerjee
- Pushpak Bhattacharyya
tags:
- Natural language processing
- Indic languages
- Machine translation
- Low-resource languages
- Unsupervised neural machine translation
categories: []
date: '2021-12-01'
lastmod: 2023-01-06T14:15:57+05:30
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
publishDate: '2023-01-06T08:45:57.189063Z'
publication_types:
- '2'
abstract: Unsupervised Neural Machine Translation (UNMT) approaches have gained widespread
  popularity in recent times. Though these approaches show impressive translation
  performance using only monolingual corpora of the languages involved, these approaches
  have mostly been tried on high-resource European language pairs viz.English–French,
  English–German, etc. In this paper, we explore UNMT for 6 Indic language pairs viz.,
  Hindi–Bengali, Hindi–Gujarati, Hindi–Marathi, Hindi–Malayalam, Hindi–Tamil, and
  Hindi–Telugu which are low-resource language pairs. We additionally perform experiments
  on 4 European language pairs viz., English–Czech, English–Estonian, English–Lithuanian,
  and English–Finnish. We observe that the lexical divergence within these language
  pairs plays a big role in the success of UNMT. In this context, we explore three
  approaches viz.,&nbsp;(i) script conversion, (ii) unsupervised bilingual embedding-based
  initialization to bring the vocabulary of the two languages closer, and (iii) dictionary
  word substitution using a bilingual dictionary. We found that the script conversion
  using a simple rule-based system benefits language pairs that have high cognate
  overlap but use different scripts. We observe that script conversion combined with
  word substitution using a dictionary further improves the UNMT performance. We use
  a ground truth bilingual dictionary in our dictionary word substitution experiments,
  and such dictionaries can also be obtained using unsupervised bilingual embeddings.
  We empirically demonstrate that minimizing lexical divergence using simple heuristics
  leads to significant improvements in the BLEU score for both related and distant
  language pairs.
publication: '*Machine Translation*'
doi: 10.1007/s10590-021-09292-y
links:
- name: URL
  url: https://doi.org/10.1007/s10590-021-09292-y
---

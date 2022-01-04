---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Role of Language Relatedness in Multilingual Fine-tuning of Language Models:
  A Case Study in Indo-Aryan Languages'
subtitle: ''
summary: ''
authors:
- Tejas Dhamecha
- Rudra Murthy
- Samarth Bharadwaj
- Karthik Sankaranarayanan
- Pushpak Bhattacharyya
tags: []
categories: []
date: '2021-11-01'
lastmod: 2022-01-04T19:19:22+05:30
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
publishDate: '2022-01-04T13:49:21.955460Z'
publication_types:
- '1'
abstract: We explore the impact of leveraging the relatedness of languages that belong
  to the same family in NLP models using multilingual fine-tuning. We hypothesize
  and validate that multilingual fine-tuning of pre-trained language models can yield
  better performance on downstream NLP applications, compared to models fine-tuned
  on individual languages. A first of its kind detailed study is presented to track
  performance change as languages are added to a base language in a graded and greedy
  (in the sense of best boost of performance) manner; which reveals that careful selection
  of subset of related languages can significantly improve performance than utilizing
  all related languages. The Indo-Aryan (IA) language family is chosen for the study,
  the exact languages being Bengali, Gujarati, Hindi, Marathi, Oriya, Punjabi and
  Urdu. The script barrier is crossed by simple rule-based transliteration of the
  text of all languages to Devanagari. Experiments are performed on mBERT, IndicBERT,
  MuRIL and two RoBERTa-based LMs, the last two being pre-trained by us. Low resource
  languages, such as Oriya and Punjabi, are found to be the largest beneficiaries
  of multilingual fine-tuning. Textual Entailment, Entity Classification, Section
  Title Prediction, tasks of IndicGLUE and POS tagging form our test bed. Compared
  to monolingual fine tuning we get relative performance improvement of up to 150%
  in the downstream tasks. The surprise take-away is that for any language there is
  a particular combination of other languages which yields the best performance, and
  any additional language is in fact detrimental.
publication: '*Proceedings of the 2021 Conference on Empirical Methods in Natural
  Language Processing*'
doi: 10.18653/v1/2021.emnlp-main.675
links:
- name: URL
  url: https://aclanthology.org/2021.emnlp-main.675
---

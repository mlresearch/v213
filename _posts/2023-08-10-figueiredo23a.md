---
title: 'Distinguishing Cause from Effect on Categorical Data: The Uniform Channel
  Model'
section: Oral
openreview: 7IyjmYBxokW
abstract: Distinguishing cause from effect using observations of a pair of random
  variables is a core problem in causal discovery. Most approaches proposed for this
  task, namely additive noise models (ANM), are only adequate for quantitative data.
  We propose a criterion to address the cause-effect problem with categorical variables
  (living in sets with no meaningful order), inspired by seeing a conditional probability
  mass function (pmf) as a discrete memoryless channel. We select as the most likely
  causal direction the one in which the conditional pmf is closer to a uniform channel
  (UC). The rationale is that, in a UC, as in an ANM, the conditional entropy (of
  the effect given the cause) is independent of the cause distribution, in agreement
  with the principle of independence of cause and mechanism. Our approach, which we
  call the uniform channel model (UCM), thus extends the ANM rationale to categorical
  variables. To assess how close a conditional pmf (estimated from data) is to a UC,
  we use statistical testing, supported by a closed-form estimate of a UC channel.
  On the theoretical front, we prove identifiability of the UCM and show its equivalence
  with a structural causal model with a low-cardinality exogenous variable. Finally,
  the proposed method compares favorably with recent state-of-the-art alternatives
  in experiments on synthetic, benchmark, and real data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: figueiredo23a
month: 0
tex_title: 'Distinguishing Cause from Effect on Categorical Data: The Uniform Channel
  Model'
firstpage: 122
lastpage: 141
page: 122-141
order: 122
cycles: false
bibtex_author: Figueiredo, Mario A. T. and Oliveira, Catarina
author:
- given: Mario A. T.
  family: Figueiredo
- given: Catarina
  family: Oliveira
date: 2023-08-10
address:
container-title: Proceedings of the Second Conference on Causal Learning and Reasoning
volume: '213'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 8
  - 10
pdf: https://proceedings.mlr.press/v213/figueiredo23a/figueiredo23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

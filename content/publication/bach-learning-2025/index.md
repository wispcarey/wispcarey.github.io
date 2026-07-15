---
title: "Learning Enhanced Ensemble Filters"
authors:
- Eviatar Bach
- Ricardo Baptista
- Edoardo Calvello
- Bohan Chen
- Andrew Stuart
date: '2026-02-15'
publishDate: '2025-12-04T00:00:00Z'
publication_types:
- article-journal
publication: '*Journal of Computational Physics*, 547, 114550'
doi: 10.1016/j.jcp.2025.114550
abstract: >
  The filtering distribution in hidden Markov models evolves according to the law of a
  mean-field model in state–observation space. The ensemble Kalman filter (EnKF)
  approximates this mean-field model with an ensemble of interacting particles, employing
  a Gaussian ansatz for the joint distribution of the state and observation at each
  observation time. These methods are robust, but the Gaussian ansatz limits accuracy.
  We address this shortcoming by using machine learning to map the joint predicted state
  and observation to the updated state estimate. A novel form of neural operator taking
  probability distributions as input—a measure neural mapping (MNM)—is used to design
  the MNM-enhanced ensemble filter (MNMEF). The ensemble method is implemented using a
  set transformer, which is invariant to ensemble permutation and allows the same basic
  parameterization to be deployed at different ensemble sizes. Fine-tuning a small number
  of ensemble-size-specific parameters further improves accuracy. Experiments demonstrate
  superior root-mean-square-error performance relative to leading filtering methods on
  Lorenz-96 and Kuramoto–Sivashinsky models.
tags:
- Ensemble Kalman Filter
- Data Assimilation
- Measure Neural Mapping
- Neural Operator
- Set Transformer
- Mean-Field Methods
- Ensemble Methods
- Machine Learning
- Computational Physics
links:
- name: Journal
  url: https://www.sciencedirect.com/science/article/pii/S0021999125008320
- name: PDF
  url: /publication/bach-learning-2025/Learning%20Enhanced%20Ensemble%20Filters.pdf
- name: arXiv
  url: https://arxiv.org/abs/2504.17836
- name: Code
  url: https://github.com/wispcarey/DALearning
- name: DOI
  url: https://doi.org/10.1016/j.jcp.2025.114550
featured: true
---

This work introduces the **measure neural mapping enhanced ensemble filter (MNMEF)**,
a learning-based data-assimilation method derived from a mean-field formulation of the
filtering problem. Measure neural mappings extend neural operators to maps acting on
probability measures; their finite-ensemble implementation uses a permutation-invariant set
transformer.

The mean-field construction allows most learned parameters to be shared across ensemble
sizes. A model can therefore be trained efficiently using a small ensemble and deployed at
other ensemble sizes, while lightweight fine-tuning adapts a limited number of parameters
such as inflation and localization.

Experiments on Lorenz-63, Lorenz-96, and Kuramoto–Sivashinsky systems show improved
filtering accuracy relative to optimized classical ensemble methods across both small and
larger ensembles.

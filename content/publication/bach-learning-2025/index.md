---
title: Learning Enhanced Ensemble Filters
authors:
- Eviatar Bach
- Ricardo Baptista
- Edoardo Calvello
- Bohan Chen
- Andrew Stuart
date: '2025-04-24'
publishDate: '2025-11-01T00:00:00Z'
publication_types:
- preprint
publication: '*arXiv*'
doi: 10.48550/arXiv.2504.17836
abstract: >
  The filtering distribution in hidden Markov models evolves according to the law
  of a mean-field model in state-observation space. The ensemble Kalman filter
  (EnKF) approximates this mean-field model with an ensemble of interacting particles,
  employing a Gaussian ansatz for the joint distribution of the state and observation
  at each observation time. These methods are robust, but the Gaussian ansatz limits
  accuracy. This shortcoming is addressed by approximating the mean-field evolution
  using a novel form of neural operator taking probability distributions as input:
  a measure neural mapping (MNM). A MNM is used to design a novel approach to filtering,
  the MNM-enhanced ensemble filter (MNMEF), which is defined in both the mean-field
  limit and for interacting ensemble particle approximations. The ensemble approach
  uses empirical measures as input to the MNM and is implemented using the set transformer,
  which is invariant to ensemble permutation and allows for different ensemble sizes.
  The derivation of methods from a mean-field formulation allows a single parameterization
  of the algorithm to be deployed at different ensemble sizes. In practice fine-tuning
  of a small number of parameters, for specific ensemble sizes, further enhances the
  accuracy of the scheme. The promise of the approach is demonstrated by its superior
  root mean-square-error performance relative to leading methods in filtering the
  Lorenz 96 and Kuramoto-Sivashinsky models.
tags:
- Ensemble Kalman Filter
- Data Assimilation
- Neural Operator
- Machine Learning (stat.ML)
- Systems and Control (eess.SY)
- Computational Physics (physics.comp-ph)
links:
- name: arXiv
  url: https://arxiv.org/abs/2504.17836
- name: DOI
  url: https://doi.org/10.48550/arXiv.2504.17836
featured: true   
---

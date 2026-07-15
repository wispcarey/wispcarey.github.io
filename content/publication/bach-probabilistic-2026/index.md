---
title: "Learning Probabilistic Filters with Strictly Proper Scoring Rules"
authors:
- Eviatar Bach
- Ricardo Baptista
- Jochen Bröcker
- Bohan Chen
- Andrew Stuart
date: '2026-06-25'
publishDate: '2026-06-25T00:00:00Z'
publication_types:
- preprint
publication: 'Submitted to the *Journal of Machine Learning Research*'
doi: 10.48550/arXiv.2606.26497
abstract: >
  Bayesian filtering of partially and noisily observed dynamical systems seeks to infer
  the evolving conditional distribution of the state of a dynamical system, given
  observations, in an online fashion. This Bayesian filtering distribution is the natural
  object for uncertainty quantification, but it is rarely available as a supervised learning
  target. However, one can often use the forecast model to generate synthetic system
  trajectories, along with synthetic observations. We introduce the proper scoring ensemble
  filter (PSEF), an ensemble data assimilation method based on training an analysis map to
  approximate the filtering distribution using only synthetic state–observation trajectories.
  The analysis step is represented as a permutation-invariant, transformer-based map that
  takes as input a forecast ensemble and observations, producing an analysis ensemble.
  Training is based on strictly proper scoring rules—with the energy score used in our
  implementation—so that probabilistic accuracy is rewarded over the whole probability
  distribution. We prove that, under a realizability assumption, the population objective
  is minimized by the true Bayesian filtering distribution. We also derive the
  finite-ensemble empirical objective used in training and relate its single
  state–observation trajectory form to the population objective, using a mean-field
  consistency argument. Numerical experiments show that the learned filter accurately
  approximates challenging filtering distributions, including nonlinear, non-Gaussian,
  and multi-modal posteriors, and achieves stronger performance in data assimilation tasks
  than classical methods or learning-based methods with mean-squared-error objectives.
  For close-to-Gaussian problems, learning a correction to the EnKF is the best approach,
  while for highly non-Gaussian problems an end-to-end approach that discards this
  inductive bias is superior.
tags:
- Proper Scoring Rules
- Proper Scoring Ensemble Filter
- Bayesian Filtering
- Data Assimilation
- Ensemble Methods
- Uncertainty Quantification
- Amortized Bayesian Inference
- Set Transformer
- Probabilistic Machine Learning
- cs.LG
- math.DS
- stat.ML
links:
- name: JMLR
  url: https://www.jmlr.org/
- name: arXiv
  url: https://arxiv.org/abs/2606.26497
- name: PDF
  url: /publication/bach-probabilistic-2026/Learning-Probabilistic-Filters-with-Strictly-Proper-Scoring-Rules.pdf
- name: Code
  url: https://github.com/wispcarey/Proper-Scoring-Ensemble-Filter
- name: DOI
  url: https://doi.org/10.48550/arXiv.2606.26497
featured: true
---

The **proper scoring ensemble filter (PSEF)** learns an ensemble analysis operator that
targets the complete Bayesian filtering distribution rather than only its conditional mean.
The operator takes a forecast ensemble and a new observation as input and returns an
analysis ensemble. A permutation-invariant transformer ensures that the result respects the
exchangeability of ensemble members and can be evaluated at different ensemble sizes.

The key training device is a **strictly proper scoring rule**, implemented with the energy
score. Its expected value is uniquely minimized by the true filtering distribution, yet its
empirical form requires only simulated state–observation trajectories—not direct access to
the generally intractable filtering distribution. Under a realizability assumption, the
population objective recovers the Bayesian filter, and a mean-field time-averaging argument
connects the practical single-trajectory objective to this population target.

Experiments cover a linear–Gaussian diagnostic, the strongly non-Gaussian doubling-angle
model, Lorenz-63, and Lorenz-96. Energy-score training captures multimodal distributions
missed by Gaussian filters and mean-based learning objectives. The results also reveal a
useful architectural distinction: an EnKF correction provides an effective inductive bias in
close-to-Gaussian problems, while a flexible end-to-end update is better suited to strongly
non-Gaussian posterior geometry.

The manuscript has been submitted to the **Journal of Machine Learning Research**.

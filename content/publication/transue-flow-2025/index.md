---
title: "Flow Matching for Efficient and Scalable Data Assimilation"
authors:
- Taos Transue
- Bohan Chen
- So Takao
- Bao Wang
date: '2026-06-15'
publishDate: '2026-06-15T00:00:00Z'
publication_types:
- article-journal
publication: '*SIAM/ASA Journal on Uncertainty Quantification* (accepted for publication)'
doi: 10.48550/arXiv.2508.13313
abstract: >
  Data assimilation (DA) estimates a dynamical system’s state from noisy observations.
  Recent generative models like the ensemble score filter (EnSF) improve DA in
  high-dimensional nonlinear settings but are computationally expensive. We introduce
  the ensemble flow filter (EnFF), a training-free, flow matching (FM)-based framework
  that accelerates sampling and offers flexibility in flow design. EnFF uses Monte
  Carlo estimators for the marginal flow field, localized guidance for observation
  assimilation, and utilizes a novel flow path that exploits the Bayesian DA
  formulation. It generalizes classical filters such as the bootstrap particle filter
  and ensemble Kalman filter. Experiments on high-dimensional benchmarks demonstrate
  EnFF’s improved cost-accuracy tradeoffs and scalability, highlighting FM’s potential
  for efficient, scalable DA.
tags:
- Flow Matching
- Data Assimilation
- Ensemble Flow Filter
- Ensemble Methods
- Bayesian Filtering
- Uncertainty Quantification
- Generative Models
- Training-Free
- Localized Guidance
- stat.ML
- cs.LG
- math.OC
links:
- name: Journal
  url: https://www.siam.org/publications/siam-journals/siam-asa-journal-on-uncertainty-quantification/
- name: arXiv
  url: https://arxiv.org/abs/2508.13313
- name: PDF
  url: /publication/transue-flow-2025/Flow%20Matching%20for%20Efficient%20and%20Scalable%20Data%20Assimilation.pdf
- name: Code
  url: https://github.com/Utah-Math-Data-Science/Data-Assimilation-Flow-Matching
- name: DOI
  url: https://doi.org/10.48550/arXiv.2508.13313
featured: true
---

The **ensemble flow filter (EnFF)** is a training-free data-assimilation framework that
uses flow matching to transform a forecast ensemble into samples from the filtering
distribution. Its Monte Carlo flow-field estimator and localized observation guidance
avoid model training while retaining the flexibility of generative flow design.

The paper introduces a **filtering-to-predictive (F2P) flow** that uses the previous
filtering distribution, rather than a standard Gaussian, as its reference. This path is
better aligned with sequential Bayesian filtering and improves efficiency and
robustness when only a small number of sampling steps is available. The analysis also
shows how EnFF recovers the bootstrap particle filter and ensemble Kalman filter under
appropriate choices and assumptions.

Experiments span Lorenz-63, Lorenz-96, the one-dimensional Kuramoto–Sivashinsky system,
and two-dimensional Navier–Stokes equations, including state dimensions up to a
256×256 grid. Across these benchmarks, EnFF provides a strong accuracy–cost trade-off
and scales to nonlinear, high-dimensional data-assimilation problems.

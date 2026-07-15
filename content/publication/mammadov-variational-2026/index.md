---
title: "Variational Flow Maps: Make Some Noise for One-Step Conditional Generation"
authors:
- Abbas Mammadov
- So Takao
- Bohan Chen
- Ricardo Baptista
- Morteza Mardani
- Yee Whye Teh
- Julius Berner
date: '2026-07-07'
publishDate: '2026-07-14T00:00:00Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 43rd International Conference on Machine Learning (ICML 2026), PMLR 306*'
doi: 10.48550/arXiv.2603.07276
abstract: >
  Flow maps enable high-quality image generation in a single forward pass. However,
  unlike iterative diffusion models, their lack of an explicit sampling trajectory
  impedes incorporating external constraints for conditional generation and solving
  inverse problems. We put forth Variational Flow Maps, a framework for conditional
  sampling that shifts the perspective of conditioning from “guiding a sampling path”
  to “learning the proper initial noise.” Given an observation, VFM learns a noise
  adapter that outputs a noise distribution whose samples are mapped to data space by
  a flow map, respecting both the observation and the data prior. A principled
  variational objective jointly trains the adapter and flow map to improve noise-data
  alignment. Across image inverse problems, VFM produces well-calibrated conditional
  samples in one or a few steps; on ImageNet, it achieves competitive fidelity while
  sampling orders of magnitude faster than iterative diffusion and flow baselines.
tags:
- Variational Flow Maps
- Conditional Generation
- Flow Matching
- Inverse Problems
- Posterior Sampling
- Reward Alignment
- Generative Models
- Machine Learning
- Computer Vision
- ICML 2026
links:
- name: ICML 2026
  url: https://icml.cc/Conferences/2026
- name: arXiv
  url: https://arxiv.org/abs/2603.07276
- name: PDF
  url: Variational-Flow-Maps.pdf
- name: Code
  url: https://github.com/abbasmammadov/VFM
- name: DOI
  url: https://doi.org/10.48550/arXiv.2603.07276
featured: true
---

**Variational Flow Maps (VFM)** recasts conditional generation as a problem of learning
the right initial noise distribution for a pretrained or jointly trained one-step flow
map. An observation-dependent adapter transforms simple noise before the flow map sends it
to data space, enforcing the measurement while retaining the learned data prior.

A variational training objective aligns the adapted noise with the conditional target and
supports both amortized inverse-problem solving and reward-based alignment. Because the
conditioning mechanism acts before generation, VFM avoids tracing and guiding the long
sampling trajectories required by diffusion and iterative flow models.

Across image inverse problems and ImageNet conditional-generation tasks, VFM produces
diverse, well-calibrated samples in one or a few network evaluations. The results combine
competitive fidelity with orders-of-magnitude faster sampling than iterative diffusion and
flow baselines.

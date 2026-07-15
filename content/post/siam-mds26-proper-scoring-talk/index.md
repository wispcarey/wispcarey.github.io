---
title: "Invited Talk at SIAM MDS26: Learning Filtering Distributions Using Strictly Proper Scoring Rules"
summary: "I will present our work on learning nonlinear, non-Gaussian filtering distributions in a three-part minisymposium on structure-preserving data assimilation and learning."
date: 2026-07-14
slug: siam-mds26-proper-scoring-talk

authors:
  - admin

tags:
  - News
  - SIAM MDS26
  - Minisymposium
  - Proper Scoring Rules
  - Bayesian Filtering
  - Data Assimilation
  - Uncertainty Quantification
  - Dynamical Systems
---

{{< toc mobile_only=true is_open=true >}}

I am pleased to share that I will give an invited talk at the **[SIAM Conference on
Mathematics of Data Science (MDS26)](https://www.siam.org/conferences-events/siam-conferences/mds26/)**
in Salt Lake City this November.

My talk, **“Learning Filtering Distributions Using Strictly Proper Scoring Rules,”**
will be part of the minisymposium

> **Structure-Preserving Data Assimilation and Learning for Complex Dynamical
> Systems — Part I of III**

organized by **Tongtong Li** (University of Maryland, Baltimore County) and
**Lizuo Liu** (Dartmouth College). I am grateful to the organizers for the invitation
and look forward to the discussion.

## Talk at a Glance

- **Talk:** Learning Filtering Distributions Using Strictly Proper Scoring Rules
- **Minisymposium:** Structure-Preserving Data Assimilation and Learning for Complex
  Dynamical Systems — Part I of III
- **Conference:** SIAM Conference on Mathematics of Data Science (MDS26)
- **Conference dates:** November 16–20, 2026
- **Venue:** Salt Palace Convention Center, Salt Lake City, Utah, U.S.
- **Session date, time, and room:** To be announced in the official program

The detailed session assignment has not yet appeared on the
[MDS26 Program & Abstracts page](https://www.siam.org/conferences-events/siam-conferences/mds26/program/program-abstracts/).
I will update this post when SIAM publishes the schedule.

## About the Talk

Bayesian filtering seeks the evolving conditional distribution of a hidden dynamical
state given partial and noisy observations. This distribution is the natural object for
uncertainty quantification, especially when nonlinear dynamics or observations lead to
non-Gaussian and multimodal posteriors. Yet the true filtering distribution is generally
intractable and therefore unavailable as a supervised learning target.

In this talk, I will present the **proper scoring ensemble filter (PSEF)**, which learns an
ensemble analysis map using simulated state–observation trajectories. The central idea is
to train with a **strictly proper scoring rule**—the energy score in our implementation—so
that the expected objective is uniquely optimized by the full filtering distribution rather
than only its conditional mean.

Our analysis map is a permutation-invariant transformer that takes a forecast ensemble and
the latest observation as input and returns an analysis ensemble. Under a realizability
assumption, we show that the population objective recovers the Bayesian filtering
distribution. Numerical experiments demonstrate accurate filtering for nonlinear and
non-Gaussian systems, including multimodal posteriors that are missed by classical Gaussian
filters and learning methods based on mean-squared error.

This is joint work with **Eviatar Bach, Ricardo Baptista, Jochen Bröcker,** and
**Andrew Stuart**.

- **Paper:** [Learning Probabilistic Filters with Strictly Proper Scoring Rules](https://arxiv.org/abs/2606.26497)
- **Code:** [wispcarey/Proper-Scoring-Ensemble-Filter](https://github.com/wispcarey/Proper-Scoring-Ensemble-Filter)
- **Publication page and BibTeX:** [Project page](/publication/bach-probabilistic-2026/)
- **Research announcement:** [Learning the Whole Filtering Distribution with Proper Scoring Rules](/post/proper-scoring-ensemble-filter-2026/)

## Minisymposium Theme

The three-part minisymposium brings together researchers working on structure-preserving
data assimilation, inverse problems, uncertainty quantification, feature-aware learning,
and scientific machine learning. Its focus is on methods that incorporate knowledge of the
underlying dynamics—such as physical constraints, coherent structures, and informative
representations—to improve the stability, robustness, interpretability, and predictive
performance of learning and inference in nonlinear and multiscale systems.

I look forward to presenting this work and to seeing many of you in Salt Lake City!

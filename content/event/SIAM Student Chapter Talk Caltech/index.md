---
title: "Talk Announcement: SIAM Student Chapter Talk - Learnable Operators on Probability Measures for Ensemble Data Assimilation"
summary: "I will give a SIAM student chapter talk on Wednesday, March 11, 2026, 12:00-1:00 PM Pacific at ANB 213, Caltech."
date: 2026-03-04

image:
  caption: "SIAM Student Chapter Talk"

authors:
  - admin

tags:
  - SIAM
  - Caltech
  - Data Assimilation
  - Machine Learning
  - Ensemble Methods
---

{{< toc mobile_only=true is_open=true >}}

## Overview

I will give an in-person Society for Industrial and Applied Mathematics (SIAM) student chapter talk at Caltech on learnable operators for ensemble data assimilation.

## Event Details

- **Date:** Wednesday, **March 11, 2026**
- **Time:** **12:00 PM - 1:00 PM Pacific**
- **Location:** **ANB 213, Caltech**
- **Format:** In person

## Talk

**Title**  
*Learnable Operators on Probability Measures for Ensemble Data Assimilation*

**Abstract**  
Data assimilation (DA) in hidden Markov models evolves the filtering distribution via a nonlinear, measure-valued recursion that propagates uncertainty through the dynamics and updates it with observations. Classical ensemble methods such as the ensemble Kalman filter remain efficient and robust, but their Gaussian update can be inaccurate in strongly nonlinear, non-Gaussian regimes. We introduce the measure neural mapping (MNM), a learnable operator acting directly on probability measures to approximate the filtering map, leading to an MNM-enhanced ensemble filter (MNMEF) formulated both at the mean-field level and as an interacting-particle algorithm. MNMEF is implemented with the set transformer, enabling a single parameterization to transfer across ensemble sizes and the permutation invariance. We provide a theoretical foundation for this transfer by establishing a continuum limit for attention on measures: under mild regularity or boundedness assumptions, attention applied to empirical measures converges in Wasserstein distance to its continuous-measure counterpart as sample size increases. This consistency explains the observed stability of MNMEF when changing ensemble size. Empirically, shared parameters, optionally augmented with light size-specific fine-tuning, yield improved RMSE over strong baselines on Lorenz-96 and Kuramoto-Sivashinsky benchmarks.

## Presenter

*Bohan Chen, California Institute of Technology, U.S.*

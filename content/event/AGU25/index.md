---
title: "AGU25 Oral — Learning Enhanced Ensemble Filters"
summary: "AGU25 oral talk — Tue, Dec 16, 2025, 09:42–09:52 CT (07:42–07:52 PT), Session NG21A."
date: 2025-11-02

image:
  caption: "AGU Fall Meeting 2025"

authors:
  - admin

tags:
  - AGU
  - Data Assimilation
  - Machine Learning
  - Uncertainty Quantification
  - Dynamical Systems
---

## Overview

Join us at **AGU25** for an oral presentation on learning-enhanced ensemble filtering for nonlinear, non-Gaussian state estimation.

## Event Details

- **Conference:** AGU25 — New Orleans, LA  
- **Presentation Type:** Oral  
- **Session:** **NG21A** — *Advances in Data Assimilation, Data Fusion, Machine Learning, Predictability, and Uncertainty Quantification in the Geosciences I (Oral)*  
- **Date:** **Tuesday, December 16, 2025**  
- **Time:** **09:42–09:52 Central Time (CT)** / **07:42–07:52 Pacific Time (PT)**  
- **Location:** New Orleans Convention Center, **Rooms 298–299**  
- **Abstract ID:** **2000239**  
- **Talk Title:** *Learning Enhanced Ensemble Filters*

## Abstract

The filtering distribution in hidden Markov models evolves according to the law of a mean-field model in state-observation space. The ensemble Kalman filter (EnKF) approximates this mean-field model with an ensemble of interacting particles, employing a Gaussian ansatz for the joint distribution of the state and observation at each observation time. These methods are robust, but the Gaussian ansatz limits accuracy. This shortcoming is addressed by approximating the mean-field evolution using a novel form of neural operator taking probability distributions as input: a measure neural mapping (MNM). A MNM is used to design a novel approach to filtering, the MNM-enhanced ensemble filter (MNMEF), which is defined in both the mean-field limit and for interacting ensemble particle approximations. The ensemble approach uses empirical measures as input to the MNM and is implemented using the set transformer, which is invariant to ensemble permutation and allows for different ensemble sizes. The derivation of methods from a mean-field formulation allows a single parameterization of the algorithm to be deployed at different ensemble sizes. In practice fine-tuning of a small number of parameters, for specific ensemble sizes, further enhances the accuracy of the scheme. The promise of the approach is demonstrated by its superior root mean-square-error performance relative to leading methods in filtering the Lorenz 96 and Kuramoto–Sivashinsky models.

## Why Attend

- See a **measure neural mapping (MNM)** approach that treats probability measures as inputs.  
- Learn how **MNMEF** operates in both **mean-field limits** and **interacting-particle** implementations.  
- Understand why **set transformers** enable **permutation invariance** and **cross-ensemble-size** deployment.  
- Review **benchmark results** on **Lorenz-96** and **Kuramoto–Sivashinsky** showing improved RMSE.

## Presenter

**Bohan Chen** — California Institute of Technology

---

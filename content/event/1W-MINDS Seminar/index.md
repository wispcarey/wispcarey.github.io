---
title: "Talk Announcement: 1W-MINDS Seminar — Learning Enhanced Ensemble Filters"
summary: "I will give a 1W-MINDS seminar on Thursday, November 6, 2025 at 2:30 PM Eastern (11:30 AM Pacific)."
date: 2025-11-01

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: "Image credit: 1W-MINDS Seminar Series"

authors:
  - admin

tags:
  - 1W-MINDS
  - Data Assimilation
  - Dynamical Systems
  - Machine Learning
  - Transformers
---

{{< toc mobile_only=true is_open=true >}}

## Overview

I’m pleased to share that I’ll be speaking in the **1W-MINDS** seminar series. The talk will present new results on learning-augmented ensemble filtering for nonlinear, non-Gaussian state estimation.

## Event Details

- **Date:** Thursday, **November 6, 2025**  
- **Time:** **2:30 PM – 3:30 PM Eastern** (11:30 AM – 12:30 PM Pacific)  
- **Format:** Online (Zoom)  
- **Zoom:** [Join the webinar](https://msu.zoom.us/j/91622014405?pwd=0vGPEVkQyH09S7XRk5Bd7HcysW2Erz.1)  
  - **Password:** 101 *(likely not required when using the full link)*

## Talk

**Title**  
*Learning Enhanced Ensemble Filters*

**Abstract**  
The filtering distribution in hidden Markov models evolves according to a mean-field law on the joint state–observation space. While the ensemble Kalman filter (EnKF) provides a robust particle approximation, its Gaussian ansatz limits accuracy for non-Gaussian dynamics. We address this with a measure neural mapping (MNM)—a neural operator defined on probability measures—which yields the MNM-enhanced ensemble filter (MNMEF) in both the mean-field limit and as an interacting-particle algorithm. The ensemble instantiation uses a permutation-invariant set transformer, enabling a single parameterization to operate across varying ensemble sizes, with light size-specific fine-tuning further improving accuracy. Empirically, MNMEF achieves superior RMSE to leading methods on Lorenz-96 and Kuramoto–Sivashinsky benchmarks.

A central theoretical contribution establishes a continuum limit for attention on measures: attention layers fed empirical measures are consistent with their continuous-measure counterparts, with outputs converging to those from the underlying measure in Wasserstein distance as the sample size goes to infinity. This result justifies cross-size parameter sharing, explains the observed stability of MNMEF when changing ensemble sizes.

## Presenter

*Bohan Chen, California Institute of Technology, U.S.*

## Add to Calendar

- **Eastern Time:** Nov 6, 2025, 2:30–3:30 PM ET  
- **Pacific Time:** Nov 6, 2025, 11:30 AM–12:30 PM PT



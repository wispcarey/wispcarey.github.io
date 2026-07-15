---
title: 'A Novel Point Process Model for COVID-19: Multivariate Recursive Hawkes Process'
authors:
- Bohan Chen
- Pujan Shrestha
- Andrea L. Bertozzi
- George Mohler
- Frederic Schoenberg
date: '2022-01-01'
publishDate: '2024-10-29T00:57:35.642900Z'
publication_types:
- chapter
publication: '*Predicting Pandemics in a Globally Connected World, Volume 1: Toward
  a Multiscale, Multidisciplinary Framework through Modeling and Simulation*'
doi: 10.1007/978-3-030-96562-4_5
abstract: This chapter presents a novel point process model for COVID-19 transmission—the
  multivariate recursive Hawkes process, which is an extension of the recursive Hawkes
  model to the multivariate case. Equivalently the model can be viewed as an extension
  of the multivariate Hawkes model to allow for varying productivity as in the recursive
  model. Several theoretical properties of this process are stated and proved, including
  the existence of the multivariate recursive counting process and formulas for the
  mean and variance. EM-based algorithms are explored for estimating parameters of
  parametric and semi-parametric forms of the model. Additionally, an algorithm is
  presented to reconstruct the process from imprecise event times. The performance
  of the algorithms on both synthetic and real COVID-19 data sets is illustrated through
  several experiments.
tags:
- COVID-19
- Expectation-Maximization
- Hawkes Processes
- Infectious Disease Modeling
- Point Processes
- Spatiotemporal Statistics
links:
- name: Book Chapter
  url: https://link.springer.com/chapter/10.1007/978-3-030-96562-4_5
- name: PDF
  url: /publication/chen-novel-2022/COVID-19.pdf
- name: DOI
  url: https://doi.org/10.1007/978-3-030-96562-4_5
---

The **multivariate recursive Hawkes process** extends self-exciting point-process models in
two directions needed for epidemic data: transmission can interact across multiple
populations, and the productivity of events can vary recursively rather than remaining
fixed. This gives the model enough flexibility to represent heterogeneous and evolving
COVID-19 transmission patterns.

The chapter establishes existence of the counting process and derives its first two
moments. It also develops expectation-maximization procedures for parametric and
semiparametric specifications, together with a reconstruction algorithm for observations
whose event times are reported only coarsely.

Synthetic experiments validate the estimators, and applications to real COVID-19 data
illustrate how the model recovers cross-population excitation and time-varying transmission
effects from imperfect public-health records.

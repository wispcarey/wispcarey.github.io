---
title: Novel batch active learning approach and its application to synthetic aperture
  radar datasets
authors:
- James Chapman
- Bohan Chen
- Zheng Tan
- Jeff Calder
- Kevin Miller
- Andrea L. Bertozzi
date: '2023-06-13'
publishDate: '2024-10-29T00:57:35.606235Z'
publication_types:
- paper-conference
publication: '*Algorithms for Synthetic Aperture Radar Imagery XXX*'
doi: 10.1117/12.2662393
abstract: 'Active learning improves the performance of machine learning methods by
  judiciously selecting a limited number of unlabeled data points to query for labels,
  with the aim of maximally improving the underlying classifiers performance. Recent
  gains have been made using sequential active learning for synthetic aperture radar
  (SAR) data.1 In each iteration, sequential active learning selects a query set of
  size one while batch active learning selects a query set of multiple datapoints.
  While batch active learning methods exhibit greater efficiency, the challenge lies
  in maintaining model accuracy relative to sequential active learning methods. We
  developed a novel, two-part approach for batch active learning: Dijkstra’s Annulus
  Core-Set (DAC) for core-set generation and LocalMax for batch sampling. The batch
  active learning process that combines DAC and LocalMax achieves nearly identical
  accuracy as sequential active learning but is more efficient, proportional to the
  batch size. As an application, a pipeline is built based on transfer learning feature
  embedding, graph learning, DAC, and LocalMax to classify the FUSAR-Ship and OpenSARShip
  datasets. Our pipeline outperforms the state-of-the-art CNN-based methods.'
tags:
- Batch active learning
links:
- name: URL
  url: 
    https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12520/125200B/Novel-batch-active-learning-approach-and-its-application-to-synthetic/10.1117/12.2662393.full
featured: true
---

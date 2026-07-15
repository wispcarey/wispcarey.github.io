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
- Batch Active Learning
- Graph Learning
- Core-set Selection
- Dijkstra's Algorithm
- Remote Sensing
- Synthetic Aperture Radar
links:
- name: SPIE
  url: 
    https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12520/125200B/Novel-batch-active-learning-approach-and-its-application-to-synthetic/10.1117/12.2662393.full
- name: PDF
  url: /publication/chapman-novel-2023/Novel%20Batch%20Active%20Learning%20Approach.pdf
- name: DOI
  url: https://doi.org/10.1117/12.2662393
featured: true
---

The paper introduces a two-stage strategy for making **batch active learning** nearly as
accurate as sequential querying while substantially reducing the number of classifier
updates. Dijkstra's Annulus Core-Set (DAC) first constructs a representative candidate set;
LocalMax then selects a diverse batch by enforcing local maxima of the acquisition
function on the data graph.

The resulting pipeline combines transfer-learned image features, graph-based
semi-supervised learning, DAC, and LocalMax for synthetic-aperture-radar target
classification. On FUSAR-Ship and OpenSARShip, it retains the accuracy of sequential active
learning with speedups that scale with batch size and outperforms the evaluated CNN-based
baselines.

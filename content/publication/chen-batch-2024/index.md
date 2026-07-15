---
title: Batch Active Learning for Multispectral and Hyperspectral Image Segmentation
  Using Similarity Graphs
authors:
- Bohan Chen
- Kevin Miller
- Andrea L. Bertozzi
- Jon Schwenk
date: '2024-06-01'
publishDate: '2024-10-29T00:57:35.628467Z'
publication_types:
- article-journal
publication: '*Communications on Applied Mathematics and Computation*'
doi: 10.1007/s42967-023-00284-8
abstract: Graph learning, when used as a semi-supervised learning (SSL) method, performs
  well for classification tasks with a low label rate. We provide a graph-based batch
  active learning pipeline for pixel/patch neighborhood multi- or hyperspectral image
  segmentation. Our batch active learning approach selects a collection of unlabeled
  pixels that satisfy a graph local maximum constraint for the active learning acquisition
  function that determines the relative importance of each pixel to the classification.
  This work builds on recent advances in the design of novel active learning acquisition
  functions (e.g., the Model Change approach in arXiv:2110.07739) while adding important
  further developments including patch-neighborhood image analysis and batch active
  learning methods to further increase the accuracy and greatly increase the computational
  efficiency of these methods. In addition to improvements in the accuracy, our approach
  can greatly reduce the number of labeled pixels needed to achieve the same level
  of the accuracy based on randomly selected labeled pixels.
tags:
- 68T05
- 68T45
- 94A08
- Active Learning
- Batch Active Learning
- Graph Learning
- Hyperspectral Imaging
- Image Segmentation
- Multispectral Imaging
- Remote Sensing
links:
- name: Journal
  url: https://link.springer.com/article/10.1007/s42967-023-00284-8
- name: PDF
  url: /publication/chen-batch-2024/Batch%20Active%20Learning%20for%20Multispectral%20and%20Hyperspectral.pdf
- name: DOI
  url: https://doi.org/10.1007/s42967-023-00284-8
---

This paper develops a graph-based pipeline for **label-efficient multispectral and
hyperspectral image segmentation**. Pixels or local image patches are embedded as nodes of
a similarity graph, and graph Laplace learning propagates the small number of queried
labels across the image.

The batch acquisition rule selects unlabeled nodes that are local maxima of a model-change
score on the graph. This prevents a batch from concentrating on redundant nearby samples,
while patch-neighborhood features provide spatial context beyond individual spectra. The
method therefore reduces both human labeling effort and the number of expensive learning
cycles.

Experiments across remote-sensing datasets show that carefully selected batches reach a
target segmentation accuracy with far fewer labels than random sampling and retain the
effectiveness of sequential active learning at substantially lower computational cost.

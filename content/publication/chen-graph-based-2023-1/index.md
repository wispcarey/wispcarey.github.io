---
title: Graph-Based Active Learning for Surface Water and Sediment Detection in Multispectral
  Images
authors:
- Bohan Chen
- Kevin Miller
- Andrea L. Bertozzi
- Jon Schwenk
date: '2023-07-01'
publishDate: '2024-10-29T00:57:35.635819Z'
publication_types:
- paper-conference
publication: '*IGARSS 2023 - 2023 IEEE International Geoscience and Remote Sensing
  Symposium*'
doi: 10.1109/IGARSS52108.2023.10282009
abstract: We develop a graph active learning pipeline (GAP) to detect surface water
  and in-river sediment pixels in satellite images. The active learning approach is
  applied within the training process to optimally select specific pixels to generate
  a hand-labeled training set. Our method obtains higher accuracy with far fewer training
  pixels than both standard and deep learning models. According to our experiments,
  our GAP trained on a set of 3270 pixels reaches a better accuracy than the neural
  network method trained on 2.1 million pixels.
tags:
- Active Learning
- Graph Learning
- Pipelines
- Radio frequency
- Remote Sensing
- Rivers
- Sensors
- Support vector machines
- Surface Water Detection
- Training
- Training data
links:
- name: IEEE Xplore
  url: https://ieeexplore.ieee.org/abstract/document/10282009
- name: PDF
  url: /publication/chen-graph-based-2023-1/Graph-Based_Active_Learning_for_Surface_Water_and_Sediment_Detection_in_Multispectral_Images.pdf
- name: DOI
  url: https://doi.org/10.1109/IGARSS52108.2023.10282009
---

The **graph active learning pipeline (GAP)** treats multispectral pixels as nodes in a
similarity graph and uses graph Laplace learning to distinguish land, surface water, and
in-river sediment. An acquisition function identifies the pixels whose expert labels are
expected to improve the classifier most, directly targeting the expensive step of building
a hand-labeled remote-sensing dataset.

On the RiverPIXELS imagery, GAP trained with only 3,270 selected pixels surpasses the
reported neural-network baseline trained on roughly 2.1 million pixels. The result
demonstrates that graph geometry and targeted labeling can provide strong segmentation
performance when dense annotation is impractical.

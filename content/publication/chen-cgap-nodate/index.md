---
title: 'CGAP: A Hybrid Contrastive and Graph-based Active Learning Pipeline to Detect
  Water and Sediment in Multispectral Images'
authors:
- Bohan Chen
- Kevin Miller
- Andrea L. Bertozzi
- Jon Schwenk
date: 2024-06-07
publishDate: '2024-10-29T00:57:35.657572Z'
publication_types:
- article-journal
publication: '*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, 18, 446–462'
doi: 10.1109/JSTARS.2024.3493073
abstract: >
  We develop a contrastive graph-based active learning pipeline (CGAP) to identify
  surface water and near-water sediment pixels in multispectral images. CGAP enhances
  the graph-based active learning pipeline (GAP) (10.1109/IGARSS52108.2023.10282009),
  which outperforms methods such as CNN–U-Net, support vector machine (SVM), and random
  forest (RF), while requiring less training data. Active learning plays an important
  role in training-data reduction, resulting in an order of magnitude less training
  data compared with conventional methods and three or more orders of magnitude less
  compared with CNN–U-Net. Our improvements focus on boosting both the pipeline's
  robustness and efficiency by integrating a feature-embedding neural network prior to
  graph construction. This neural network, trained using contrastive learning, projects
  high-dimensional raw features into a lower-dimensional space, facilitating more
  efficient graph learning. The training process incorporates specialized augmentations
  to bolster the embedded features' resilience to geometric transformations, varying
  resolutions, and light cloud cover. Moreover, we develop a Python-based demo,
  GraphRiverClassifier (GRC), that uses Google Earth Engine and our enhanced pipeline to
  provide a user-friendly tool for rapid and accurate surface-water and sediment
  analyses and algorithm testing.
tags:
- Active Learning
- Contrastive Learning
- Graph Learning
- Image Segmentation
- Multispectral Imaging
- Remote Sensing
- Rivers
- Surface Water Detection
links:
- name: IEEE Xplore
  url: https://ieeexplore.ieee.org/document/10747084
- name: TechRxiv
  url: https://doi.org/10.36227/techrxiv.171778689.93223348
- name: PDF
  url: /publication/chen-cgap-nodate/CGAP.pdf
- name: Code
  url: https://github.com/wispcarey/CGAP-SurfaceWaterDetection
- name: Demo
  url: https://github.com/wispcarey/GraphRiverClassifier
- name: DOI
  url: https://doi.org/10.1109/JSTARS.2024.3493073
featured: true
---

The **contrastive graph-based active learning pipeline (CGAP)** combines a learned feature
embedding with graph Laplace learning to classify land, surface water, and near-water
sediment in Landsat imagery. Custom contrastive augmentations make the features robust to
geometric transformations, changes in spatial resolution, and light cloud cover while
reducing the dimension used for graph construction.

CGAP includes a basic version trained from the labeled RiverPIXELS dataset and an adaptive
version that uses active learning to guide a human-in-the-loop labeling process. A compact
representative set is joined with each test image to form a graph, allowing label
propagation without constructing one prohibitively large graph over every training pixel.

The experiments show stronger boundary and overall accuracy than the preceding GAP,
support-vector-machine, random-forest, and DeepWaterMap baselines, using orders of magnitude
less labeled data than a CNN–U-Net pipeline. The accompanying **GraphRiverClassifier**
connects the trained model to Google Earth Engine and Colab for rapid analysis of arbitrary
Landsat scenes.

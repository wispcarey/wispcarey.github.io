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
abstract: We develop a contrastive graph-based active learning pipeline (CGAP) to identify surface water and near-water sediment pixels in multispectral images. CGAP enhances the graph-based active learning pipeline (GAP) (10.1109/IGARSS52108.2023.10282009), which outperforms methods such as CNN-Unet, support vector machine (SVM), and random forest (RF), while requiring less training data. Active learning plays an important role for training data reduction, resulting in an order of magintude less training data compared with conventional methods and three or more orders of magnitude less compared with CNN-Unet. Our improvements focus on boosting both the pipeline's robustness and efficiency by integrating a feature-embedding neural network prior to graph construction. This neural network, trained using contrastive learning, performs effective data dimension reduction by projecting high-dimensional raw features into a lower-dimensional space, thereby facilitating more efficient graph learning. The training process incorporates specialized augmentations to bolster the embedded features' resilience to geometric transformations, varying resolutions, and light cloud cover. Moreover, we develop a Python-based demo, GraphRiverClassifier (GRC), that uses the Google Earth Engine and our enhanced pipeline to provide a user-friendly tool for rapid and accurate surface water and sediment analyses and rapid testing of algorithm performances.
links:
- name: URL
  url: 
    https://ieeexplore.ieee.org/document/10747084
---

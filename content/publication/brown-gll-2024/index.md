---
title: "GLL: A Differentiable Graph Learning Layer for Neural Networks"
authors:
- Jason Brown
- Bohan Chen
- Harris Hardiman-Mostow
- Jeff Calder
- Andrea L. Bertozzi
date: '2024-12-11'
publishDate: '2024-12-11T01:54:29Z'
publication_types:
- paper-preprint
publication: '*arXiv*'
doi: 10.48550/arXiv.2412.08016
abstract: 'Standard deep learning architectures used for classification generate label predictions with a projection head and softmax activation function. Although successful, these methods fail to leverage the relational information between samples in the batch for generating label predictions. In recent works, graph-based learning techniques, namely Laplace learning, have been heuristically combined with neural networks for both supervised and semi-supervised learning (SSL) tasks. However, prior works approximate the gradient of the loss function with respect to the graph learning algorithm or decouple the processes; end-to-end integration with neural networks is not achieved. In this work, we derive backpropagation equations, via the adjoint method, for inclusion of a general family of graph learning layers into a neural network. This allows us to precisely integrate graph Laplacian-based label propagation into a neural network layer, replacing a projection head and softmax activation function for classification tasks. Using this new framework, our experimental results demonstrate smooth label transitions across data, improved robustness to adversarial attacks, improved generalization, and improved training dynamics compared to the standard softmax-based approach. Our code is available at https://github.com/jwcalder/GraphLearningLayer'
tags:
- Graph Learning, Label Propagation, Adversarial Robustness, Semi-supervised Learning, End-to-end Integration
links:
- name: arXiv abstract
  url: https://arxiv.org/abs/2412.08016
- name: DOI
  url: https://doi.org/10.48550/arXiv.2412.08016
featured: true
---

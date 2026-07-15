---
title: 'AutoKG: Efficient Automated Knowledge Graph Generation for Language Models'
authors:
- Bohan Chen
- Andrea L. Bertozzi
date: '2023-12-18'
publishDate: '2024-10-29T00:57:35.613756Z'
publication_types:
- paper-conference
publication: '*2023 IEEE International Conference on Big Data (BigData)*'
doi: 10.1109/BigData59044.2023.10386454
abstract: Traditional methods of linking large language models (LLMs) to knowledge
  bases via the semantic similarity search often fall short of capturing complex relational
  dynamics. To address these limitations, we introduce AutoKG, a lightweight and efficient
  approach for automated knowledge graph (KG) construction. For a given knowledge
  base consisting of text blocks, AutoKG first extracts keywords using a LLM and then
  evaluates the relationship weight between each pair of keywords using graph Laplace
  learning. We employ a hybrid search scheme combining vector similarity and graph-based
  associations to enrich LLM responses. Preliminary experiments demonstrate that AutoKG
  offers a more comprehensive and interconnected knowledge retrieval mechanism compared
  to the semantic similarity search, thereby enhancing the capabilities of LLMs in
  generating more insightful and relevant outputs.
tags:
- Knowledge Graphs
- Large Language Models
- Retrieval-Augmented Generation
- Graph Laplacian
- Graph Learning
- Hybrid Search
- Natural Language Processing
links:
- name: IEEE Xplore
  url: https://ieeexplore.ieee.org/abstract/document/10386454
- name: arXiv
  url: https://arxiv.org/abs/2311.14740
- name: PDF
  url: /publication/chen-autokg-2023/AutoKG_Efficient_Automated_Knowledge_Graph_Generation_for_Language_Models.pdf
- name: Code
  url: https://github.com/wispcarey/AutoKG
- name: DOI
  url: https://doi.org/10.1109/BigData59044.2023.10386454
featured: true
---

**AutoKG** is a lightweight pipeline for turning an unstructured text collection into a
knowledge graph that can augment a large language model. An LLM extracts keywords from
text blocks, and graph Laplace learning estimates relationships between keyword pairs
without requiring a hand-designed ontology or end-to-end model fine-tuning.

At query time, AutoKG combines standard vector similarity with graph-guided retrieval.
The vector search identifies semantically relevant text blocks, while the graph expands
the search toward strongly associated keywords and their supporting passages. The merged
context exposes relational information that a nearest-neighbor search can miss.

Experiments on question answering and knowledge discovery show that this hybrid retrieval
mechanism returns more interconnected context and helps the language model produce more
relevant and informative responses. The paper appeared in the GTA3 workshop at **IEEE
BigData 2023**, and the complete demonstration notebooks are publicly available.

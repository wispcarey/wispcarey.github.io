---
title: Narrative Analysis of True Crime Podcasts With Knowledge Graph-Augmented Large Language Models
authors:
- James Chapman
- Xinyi Leng
- Jason Liang
- Jack Mauro
- Xu Wang
- Andrea L. Bertozzi
- Junyuan Lin
- Bohan Chen
- Chenchen Ye
- Temple Daniel
- P. Jeffrey Brantingham
date: '2024-10-01'
publishDate: '2025-11-01T00:00:00Z'
publication_types:
- paper-conference
publication: '*Proceedings of ACM Conference (GTA3 Workshop at the 33rd ACM International Conference on Information and Knowledge Management, 2024)*'
abstract: >
  Narrative data spans all disciplines and provides a coherent model of the world to the reader or viewer. Large Language Models (LLMs) have advanced natural language analysis but still struggle with complex, conflicting narrative arcs. This work analyzes true-crime podcast data (Serial) using knowledge graphs (KGs) with both classical NLP and LLM approaches, and directly compares KG-augmented LLMs (KGLLMs) with classical methods for KG construction, topic modeling, and sentiment analysis. The KGLLM enables natural-language querying of the knowledge base, factual Q&A, and robustness testing under adversarial prompting. Results indicate KGLLMs outperform standard LLMs on multiple metrics, show greater robustness to adversarial prompts, and better summarize text into topics.
tags:
- Narrative Analysis
- Large Language Models
- Knowledge Graphs
- Adversarial Robustness
- Hearsay
- Sentiment
- Topic Modeling
- True Crime
links:
- name: NSF Public Access
  url: https://par.nsf.gov/biblio/10608878
- name: PDF
  url: https://par.nsf.gov/servlets/purl/10608878
---

This work develops a **knowledge-graph-augmented language-model pipeline** for analyzing
long, contested narratives. Using the first season of the *Serial* true-crime podcast as a
case study, the system organizes people, claims, events, and relationships into a structure
that can be queried while preserving connections across episodes and competing accounts.

The study compares classical NLP and LLM-based approaches to knowledge-graph construction,
topic modeling, and sentiment analysis. It then uses the graph as retrieval context for
natural-language question answering and evaluates the resulting KGLLM under factual and
adversarial prompts. The graph-augmented model gives more grounded answers, produces more
coherent topic summaries, and is more robust to misleading prompts than an unaugmented LLM.

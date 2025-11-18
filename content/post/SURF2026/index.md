---
title: 🎉 Caltech SURF 2026
summary: I will be a mentor for the Caltech Summer Undergraduate Research Fellowships (SURF) program in 2026.
date: 2025-11-10

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
# image:
#   caption: 'Image credit: [Caltech Photos](https://filming.caltech.edu/photos)'

authors:
  - admin

tags:
  - SURF
  - Caltech
  - Mentoring
  - Data Assimilation
  - Machine Learning Theory
---

{{< toc mobile_only=true is_open=true >}}

## Overview

The Summer Undergraduate Research Fellowships (SURF) program is one of the "crown jewels" of Caltech. Since 1979, SURF students have had the opportunity to conduct research under the guidance of experienced mentors working at the frontier of their fields.

In 2026, I will serve again as a mentor in the SURF program.

This year, there will be **two main research directions** available:

1. **Machine Learning for Data Assimilation**
2. **Machine Learning Theory, with a focus on Attention Mechanisms and Transformers**

You may indicate your preferred direction in your application; I am happy to discuss which option is a better fit for your background and interests.

## Research Focus

### 1. Machine Learning for Data Assimilation

This direction will explore accessible yet meaningful problems in **data assimilation (DA)**, with an emphasis on how **machine learning methods** can enhance or complement classical DA techniques.

Possible topics include (but are not limited to):

- Designing **ML-augmented ensemble filters** that are *amortized* over families of observation operators and noise levels, so that a single learned component can adapt efficiently to changing observation models and uncertainty structures.
- Using **machine learning to approximate optimal particle filters**, with learned mechanisms that jointly improve both the **prediction** (propagation) step and the **analysis** (update) step, aiming for better stability, accuracy, and computational efficiency.

The project is designed to be manageable. I will provide detailed guidance, including theoretical background in both DA and ML, as well as relevant code resources. A typical workflow may include reading and discussing selected papers, implementing algorithms in Python, running controlled numerical experiments, and analyzing the results.

My hope is to collaborate closely with the students to produce a research paper by the end of the project. However, if our results are not substantial enough for a publication, that is completely fine. My primary goal is for you to gain a solid understanding and valuable skills in DA and ML.

**References:**

- [Machine Learning for Inverse Problems and Data Assimilation](https://arxiv.org/abs/2410.10523)
- [Learning Enhanced Ensemble Filters](https://arxiv.org/abs/2504.17836)
- [Ensemble Kalman Methods: A Mean Field Perspective](https://arxiv.org/abs/2209.11371)

### 2. Machine Learning Theory: Attention Mechanisms and Transformers

This direction will use **carefully designed experiments to explore questions in modern machine learning theory**, with a particular focus on the role of the **activation function inside the attention mechanism** of Transformer architectures.

According to my current theoretical work, under certain assumptions, the conventional choice of softmax in attention may **not** be theoretically optimal. Motivated by this, I would like SURF students to systematically investigate, through experiments, how replacing softmax with alternative activation functions changes the behavior and performance of Transformers.

In this project, you may:

- Implement Transformer variants in which the attention weights are produced by **different activation functions** (for example, polynomial activations, ReLU-type alternatives, or normalization-based replacements for softmax).
- Design and run experiments on **benchmark tasks** to compare these variants in terms of accuracy, stability, and training dynamics.
- Probe how the **optimization, generalization, and robustness** of these models relate to the theoretical predictions that I am developing.

There is already a growing empirical literature on **softmax-free or softmax-alternative attention mechanisms**. This project is designed to complement those works from a **theory-first perspective**: I will start from theoretical analysis to derive concrete hypotheses, and you will help test these hypotheses experimentally. Through this process, you will both:

- Gain a **deeper understanding of the theory behind Transformers and attention**, and  
- Build **practical experience** implementing and training modern Transformer-style models.

**References:**

- [cosFormer: Rethinking Softmax in Attention](https://arxiv.org/abs/2202.08791)  
- [Rethinking Attention: Polynomial Alternatives to Softmax in Transformers](https://arxiv.org/abs/2410.18613)  
- [Replacing Softmax with ReLU in Vision Transformers](https://arxiv.org/abs/2309.08586)  
- [SimA: Simple Softmax-free Attention for Vision Transformers](https://arxiv.org/abs/2206.08898)


## Expectations for Students

My primary expectation is that you bring **genuine enthusiasm** to this project. Please make sure that at least one of the two general research directions outlined above aligns with your interests and that you are willing to dedicate time and effort to it over the summer of 2026.

In terms of skills, it would be very helpful if you have:

- A foundational understanding of **probability**, **stochastic processes**, **(ordinary) differential equations**, and **linear algebra** (ideally from coursework).
- Solid **coding proficiency**, especially in **Python**; experience with **PyTorch** (or a similar framework) is helpful but not strictly required—I am happy to provide guidance.

Passion and curiosity are the key qualities I am looking for. If you are excited about these topics and ready to engage deeply, I believe you will find this project both rewarding and educational.

## References for SURF

For more information on the SURF program, please refer to the official [Caltech SURF page](https://sfp.caltech.edu/undergraduate-research/programs/surf). This page provides additional links to details about the program, including:

- [Eligibility](https://sfp.caltech.edu/undergraduate-research/programs/surf/eligibility_requirements)  
- [Application Information](https://sfp.caltech.edu/undergraduate-research/programs/surf/application_information)  
- [Announcements of Opportunity](http://announcements.surf.caltech.edu/index.cfm?event=ShowAOPublicList&inFrame=&type=SURF&formType=AO_CIT)  
- [FAQs](https://sfp.caltech.edu/undergraduate-research/programs/surf/faqs)

## Acknowledgments

I would like to extend my heartfelt thanks to my supervisor, Professor Andrew Stuart, for his invaluable support in my role as a SURF mentor. His guidance and encouragement have been instrumental in enabling me to participate in this program and share these opportunities with undergraduate students.

## License

Copyright 2024-present [Bohan Chen](https://chenbh.com).

Released under the [MIT](https://github.com/wispcarey/wispcarey.github.io/blob/main/LICENSE.md) license.

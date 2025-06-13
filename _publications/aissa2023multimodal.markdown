---
layout: publication
title: 'Multimodal Representations For Teacher-guided Compositional Visual Reasoning'
authors: Wafa Cedric - Vertigo Aissa, Marin Cedric - Vertigo Ferecatu, Michel Cedric - Vertigo Crucianu
conference: "Advanced Concepts for Intelligent Vision Systems 21st International Conference (ACIVS 2023) Aug 2023 Kumamoto Japan"
year: 2023
bibkey: aissa2023multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.15585'}
tags: ['Interpretability and Explainability', 'Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Neural Module Networks (NMN) are a compelling method for visual question
answering, enabling the translation of a question into a program consisting of
a series of reasoning sub-tasks that are sequentially executed on the image to
produce an answer. NMNs provide enhanced explainability compared to integrated
models, allowing for a better understanding of the underlying reasoning
process. To improve the effectiveness of NMNs we propose to exploit features
obtained by a large-scale cross-modal encoder. Also, the current training
approach of NMNs relies on the propagation of module outputs to subsequent
modules, leading to the accumulation of prediction errors and the generation of
false answers. To mitigate this, we introduce an NMN learning strategy
involving scheduled teacher guidance. Initially, the model is fully guided by
the ground-truth intermediate outputs, but gradually transitions to an
autonomous behavior as training progresses. This reduces error accumulation,
thus improving training efficiency and final performance.We demonstrate that by
incorporating cross-modal features and employing more effective training
techniques for NMN, we achieve a favorable balance between performance and
transparency in the reasoning process.

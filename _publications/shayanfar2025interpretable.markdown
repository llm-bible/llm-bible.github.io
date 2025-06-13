---
layout: publication
title: 'Codial: Interpretable Task-oriented Dialogue Systems Through Dialogue Flow Alignment'
authors: Radin Shayanfar, Chu Fei Luo, Rohan Bhambhoria, Samuel Dahan, Xiaodan Zhu
conference: "Arxiv"
year: 2025
bibkey: shayanfar2025interpretable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02264'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Applications', 'Tools']
---
It is often challenging to teach specialized, unseen tasks to dialogue systems due to the high cost of expert knowledge, training data, and high technical difficulty. To support domain-specific applications - such as law, medicine, or finance - it is essential to build frameworks that enable non-technical experts to define, test, and refine system behaviour with minimal effort. Achieving this requires cross-disciplinary collaboration between developers and domain specialists. In this work, we introduce a novel framework, CoDial (Code for Dialogue), that converts expert knowledge, represented as a novel structured heterogeneous graph, into executable conversation logic. CoDial can be easily implemented in existing guardrailing languages, such as Colang, to enable interpretable, modifiable, and true zero-shot specification of task-oriented dialogue systems. Empirically, CoDial achieves state-of-the-art performance on the STAR dataset for inference-based models and is competitive with similar baselines on the well-known MultiWOZ dataset. We also demonstrate CoDial's iterative improvement via manual and LLM-aided feedback, making it a practical tool for expert-guided alignment of LLMs in high-stakes domains.

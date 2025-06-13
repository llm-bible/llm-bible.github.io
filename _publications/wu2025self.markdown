---
layout: publication
title: 'Self-routing RAG: Binding Selective Retrieval With Knowledge Verbalization'
authors: Di Wu, Jia-chen Gu, Kai-wei Chang, Nanyun Peng
conference: "Arxiv"
year: 2025
bibkey: wu2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01018'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Selective retrieval improves retrieval-augmented generation (RAG) by reducing
distractions from low-quality retrievals and improving efficiency. However,
existing approaches under-utilize the inherent knowledge of large language
models (LLMs), leading to suboptimal retrieval decisions and degraded
generation performance. To bridge this gap, we propose Self-Routing RAG
(SR-RAG), a novel framework that binds selective retrieval with knowledge
verbalization. SR-RAG enables an LLM to dynamically decide between external
retrieval and verbalizing its own parametric knowledge. To this end, we design
a multi-task objective that jointly optimizes an LLM on knowledge source
selection, knowledge verbalization, and response generation. We further
introduce dynamic knowledge source inference via nearest neighbor search to
improve the accuracy of knowledge source decision under domain shifts.
Fine-tuning three LLMs with SR-RAG significantly improves both their response
accuracy and inference latency. Compared to the strongest selective retrieval
baseline, SR-RAG reduces retrievals by 29% while improving the performance by
5.1%.

---
layout: publication
title: 'Order Doesn''t Matter, But Reasoning Does: Training Llms With Order-centric Augmentation'
authors: Qianxi He, Qianyu He, Jiaqing Liang, Yanghua Xiao, Weikang Zhou, Zeye Sun, Fei Yu
conference: "Arxiv"
year: 2025
bibkey: he2025order
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19907'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/Order-Centric-Data-Augmentation-822C/'}
tags: ['RAG', 'Has Code', 'Tools', 'Training Techniques']
---
Logical reasoning is essential for large language models (LLMs) to ensure
accurate and coherent inference. However, LLMs struggle with reasoning order
variations and fail to generalize across logically equivalent transformations.
LLMs often rely on fixed sequential patterns rather than true logical
understanding. To address this issue, we introduce an order-centric data
augmentation framework based on commutativity in logical reasoning. We first
randomly shuffle independent premises to introduce condition order
augmentation. For reasoning steps, we construct a directed acyclic graph (DAG)
to model dependencies between steps, which allows us to identify valid
reorderings of steps while preserving logical correctness. By leveraging
order-centric augmentations, models can develop a more flexible and generalized
reasoning process. Finally, we conduct extensive experiments across multiple
logical reasoning benchmarks, demonstrating that our method significantly
enhances LLMs' reasoning performance and adaptability to diverse logical
structures. We release our codes and augmented data in
https://anonymous.4open.science/r/Order-Centric-Data-Augmentation-822C/.

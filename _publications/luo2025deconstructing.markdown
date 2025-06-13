---
layout: publication
title: 'Deconstructing Long Chain-of-thought: A Structured Reasoning Optimization Framework For Long Cot Distillation'
authors: Yijia Luo, Yulin Song, Xingyao Zhang, Jiaheng Liu, Weixun Wang, Gengru Chen, Wenbo Su, Bo Zheng
conference: "Arxiv"
year: 2025
bibkey: luo2025deconstructing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16385'}
tags: ['Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recent advancements in large language models (LLMs) have demonstrated
remarkable reasoning capabilities through long chain-of-thought (CoT)
reasoning. The R1 distillation scheme has emerged as a promising approach for
training cost-effective models with enhanced reasoning abilities. However, the
underlying mechanisms driving its effectiveness remain unclear. This study
examines the universality of distillation data and identifies key components
that enable the efficient transfer of long-chain reasoning capabilities in LLM
distillation. Our findings reveal that the effectiveness of long CoT reasoning
distillation from teacher models like Qwen-QwQ degrades significantly on
nonhomologous models, challenging the assumed universality of current
distillation methods. To gain deeper insights into the structure and patterns
of long CoT reasoning, we propose DLCoT (Deconstructing Long Chain-of-Thought),
a distillation data enhancement framework. DLCoT consists of three key steps:
(1) data segmentation to decompose complex long CoT structures, (2)
simplification by eliminating unsolvable and redundant solutions, and (3)
optimization of intermediate error states. Our approach significantly improves
model performance and token efficiency, facilitating the development of
high-performance LLMs.

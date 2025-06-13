---
layout: publication
title: 'The Devil Is In The Details: Tackling Unimodal Spurious Correlations For Generalizable Multimodal Reward Models'
authors: Zichao Li, Xueru Wen, Jie Lou, Yuqiu Ji, Yaojie Lu, Xianpei Han, Debing Zhang, Le Sun
conference: "Arxiv"
year: 2025
bibkey: li2025devil
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03122"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Multimodal Reward Models (MM-RMs) are crucial for aligning Large Language Models (LLMs) with human preferences, particularly as LLMs increasingly interact with multimodal data. However, we find that MM-RMs trained on existing datasets often struggle to generalize to out-of-distribution data due to their reliance on unimodal spurious correlations, primarily text-only shortcuts within the training distribution, which prevents them from leveraging true multimodal reward functions. To address this, we introduce a Shortcut-aware MM-RM learning algorithm that mitigates this issue by dynamically reweighting training samples, shifting the distribution toward better multimodal understanding, and reducing dependence on unimodal spurious correlations. Our experiments demonstrate significant improvements in generalization, downstream task performance, and scalability, establishing a more robust framework for multimodal reward modeling.

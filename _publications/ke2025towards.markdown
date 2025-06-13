---
layout: publication
title: 'DWIM: Towards Tool-aware Visual Reasoning Via Discrepancy-aware Workflow Generation & Instruct-masking Tuning'
authors: Fucai Ke, Vijay Kumar B G, Xingjian Leng, Zhixi Cai, Zaid Khan, Weiqing Wang, Pari Delir Haghighi, Hamid Rezatofighi, Manmohan Chandraker
conference: "Arxiv"
year: 2025
bibkey: ke2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19263'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Visual reasoning (VR), which is crucial in many fields for enabling
human-like visual understanding, remains highly challenging. Recently,
compositional visual reasoning approaches, which leverage the reasoning
abilities of large language models (LLMs) with integrated tools to solve
problems, have shown promise as more effective strategies than end-to-end VR
methods. However, these approaches face limitations, as frozen LLMs lack tool
awareness in VR, leading to performance bottlenecks. While leveraging LLMs for
reasoning is widely used in other domains, they are not directly applicable to
VR due to limited training data, imperfect tools that introduce errors and
reduce data collection efficiency in VR, and challenging in fine-tuning on
noisy workflows. To address these challenges, we propose DWIM: i)
Discrepancy-aware training Workflow generation, which assesses tool usage and
extracts more viable workflows for training; and ii) Instruct-Masking
fine-tuning, which guides the model to only clone effective actions, enabling
the generation of more practical solutions. Our experiments demonstrate that
DWIM achieves state-of-the-art performance across various VR tasks, exhibiting
strong generalization on multiple widely-used datasets.

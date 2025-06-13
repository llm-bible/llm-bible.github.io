---
layout: publication
title: 'How To Alleviate Catastrophic Forgetting In Llms Finetuning? Hierarchical Layer-wise And Element-wise Regularization'
authors: Shezheng Song, Hao Xu, Jun Ma, Shasha Li, Long Peng, Qian Wan, Xiaodong Liu, Jie Yu
conference: "Arxiv"
year: 2025
bibkey: song2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13669"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Large Language Models (LLMs) exhibit strong general language capabilities.
However, fine-tuning these models on domain-specific tasks often leads to
catastrophic forgetting, where the model overwrites or loses essential
knowledge acquired during pretraining. This phenomenon significantly limits the
broader applicability of LLMs. To address this challenge, we propose a novel
approach to compute the element-wise importance of model parameters crucial for
preserving general knowledge during fine-tuning. Our method utilizes a
dual-objective optimization strategy: (1) regularization loss based on
element-wise parameter importance, which constrains the updates to parameters
crucial for general knowledge; (2) cross-entropy loss to adapt to
domain-specific tasks. Additionally, we introduce layer-wise coefficients to
account for the varying contributions of different layers, dynamically
balancing the dual-objective optimization. Extensive experiments on scientific,
medical, and physical tasks using GPT-J and LLaMA-3 demonstrate that our
approach mitigates catastrophic forgetting while enhancing model adaptability.
Compared to previous methods, our solution is approximately 20 times faster and
requires only 10-15% of the storage, highlighting the practical efficiency. The
code will be released.

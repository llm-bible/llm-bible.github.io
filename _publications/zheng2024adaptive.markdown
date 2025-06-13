---
layout: publication
title: 'Adaptive Pruning For Large Language Models With Structural Importance Awareness'
authors: Haotian Zheng, Jinke Ren, Yushan Sun, Ruichen Zhang, Wenbo Zhang, Zhen Li, Dusit Niyato, Shuguang Cui, Yatong Han
conference: "Arxiv"
year: 2024
bibkey: zheng2024adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15127'}
tags: ['Language Modeling', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Merging', 'Applications', 'Fine-Tuning', 'Pruning', 'Pretraining Methods']
---
The recent advancements in large language models (LLMs) have significantly
improved language understanding and generation capabilities. However, it is
difficult to deploy LLMs on resource-constrained edge devices due to their high
computational and storage resource demands. To address this issue, we propose a
novel LLM model pruning method, namely structurally-aware adaptive pruning
(SAAP), to significantly reduce the computational and memory costs while
maintaining model performance. We first define an adaptive importance fusion
metric to evaluate the importance of all coupled structures in LLMs by
considering their homoscedastic uncertainty. Then, we rank the importance of
all modules to determine the specific layers that should be pruned to meet
particular performance requirements. Furthermore, we develop a new group
fine-tuning strategy to improve the inference efficiency of LLMs. Finally, we
evaluate the proposed SAAP method on multiple LLMs across two common tasks,
i.e., zero-shot classification and text generation. Experimental results show
that our SAAP method outperforms several state-of-the-art baseline methods,
achieving 2.17%, 2.37%, and 2.39% accuracy gains on LLaMA-7B, Vicuna-7B, and
LLaMA-13B. Additionally, SAAP improves the token generation speed by 5%,
showcasing its practical advantages in resource-constrained scenarios.

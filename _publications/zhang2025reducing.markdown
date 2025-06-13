---
layout: publication
title: 'Lori: Reducing Cross-task Interference In Multi-task Low-rank Adaptation'
authors: Juzheng Zhang, Jiacheng You, Ashwinee Panda, Tom Goldstein
conference: "Arxiv"
year: 2025
bibkey: zhang2025reducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07448"}
  - {name: "Code", url: "https://github.com/juzhengz/LoRI"}
tags: ['Fine-Tuning', 'Responsible AI', 'Applications', 'RAG', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Low-Rank Adaptation (LoRA) has emerged as a popular parameter-efficient
fine-tuning (PEFT) method for Large Language Models (LLMs), yet it still incurs
notable overhead and suffers from parameter interference in multi-task
scenarios. We propose LoRA with Reduced Interference (LoRI), a simple yet
effective approach that freezes the projection matrices \\(A\\) as random
projections and sparsifies the matrices \\(B\\) using task-specific masks. This
design substantially reduces the number of trainable parameters while
maintaining strong task performance. Moreover, LoRI minimizes cross-task
interference in adapter merging by leveraging the orthogonality between adapter
subspaces, and supports continual learning by using sparsity to mitigate
catastrophic forgetting. Extensive experiments across natural language
understanding, mathematical reasoning, code generation, and safety alignment
tasks demonstrate that LoRI outperforms full fine-tuning and existing PEFT
methods, while using up to 95% fewer trainable parameters than LoRA. In
multi-task experiments, LoRI enables effective adapter merging and continual
learning with reduced cross-task interference. Code is available at:
https://github.com/juzhengz/LoRI

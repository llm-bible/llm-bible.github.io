---
layout: publication
title: 'ULPT: Prompt Tuning With Ultra-low-dimensional Optimization'
authors: Zijun Wu, Yongchang Hao, Lili Mou
conference: "Arxiv"
year: 2025
bibkey: wu2025prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04501"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models achieve state-of-the-art performance but are costly to
fine-tune due to their size. Parameter-efficient fine-tuning methods, such as
prompt tuning, address this by reducing trainable parameters while maintaining
strong performance. However, prior methods tie prompt embeddings to the model's
dimensionality, which may not scale well with larger LLMs and more customized
LLMs. In this paper, we propose Ultra-Low-dimensional Prompt Tuning (ULPT),
which optimizes prompts in a low-dimensional space (e.g., 2D) and use a random
but frozen matrix for the up-projection. To enhance alignment, we introduce
learnable shift and scale embeddings. ULPT drastically reduces the trainable
parameters, e.g., 2D only using 2% parameters compared with vanilla prompt
tuning while retaining most of the performance across 21 NLP tasks. Our
theoretical analysis shows that random projections can capture high-rank
structures effectively, and experimental results demonstrate ULPT's competitive
performance over existing parameter-efficient methods.

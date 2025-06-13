---
layout: publication
title: 'Llama-moe V2: Exploring Sparsity Of Llama From Perspective Of Mixture-of-experts With Post-training'
authors: Xiaoye Qu, Daize Dong, Xuyang Hu, Tong Zhu, Weigao Sun, Yu Cheng
conference: "Arxiv"
year: 2024
bibkey: qu2024llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15708"}
  - {name: "Code", url: "https://github.com/OpenSparseLLMs/LLaMA-MoE-v2"}
tags: ['Transformer', 'Pruning', 'Reinforcement Learning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Recently, inspired by the concept of sparsity, Mixture-of-Experts (MoE)
models have gained increasing popularity for scaling model size while keeping
the number of activated parameters constant. In this study, we thoroughly
investigate the sparsity of the dense LLaMA model by constructing MoE for both
the attention (i.e., Attention MoE) and MLP (i.e., MLP MoE) modules in the
transformer blocks. Specifically, we investigate different expert construction
methods and granularities under the same activation conditions to analyze the
impact of sparsifying the model. Additionally, to comprehensively evaluate the
model's capabilities across various domains (e.g., conversation, code, math)
after sparsification, we apply sparsity to the instructed large language models
(LLMs) and construct instructed MoE models. To counteract the performance
degradation resulting from increased sparsity, we design a two-stage
post-training strategy to enhance model performance. Experiments on the LLaMA3
model demonstrate the potential effectiveness of this approach for future
developments of instructed MoE models. The source codes and models are
available at: \url\{https://github.com/OpenSparseLLMs/LLaMA-MoE-v2\}.

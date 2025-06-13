---
layout: publication
title: 'Seerattention: Learning Intrinsic Sparse Attention In Your Llms'
authors: Yizhao Gao, Zhichen Zeng, Dayou Du, Shijie Cao, Peiyuan Zhou, Jiaxing Qi, Junjie Lai, Hayden Kwok-hay So, Ting Cao, Fan Yang, Mao Yang
conference: "Arxiv"
year: 2024
bibkey: gao2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13276"}
  - {name: "Code", url: "https://github.com/microsoft/SeerAttention"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Distillation', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Attention is the cornerstone of modern Large Language Models (LLMs). Yet its
quadratic complexity hinders efficiency and scalability, especially for
long-context processing. A promising approach is to leverage sparsity in
attention. However, existing sparsity-based solutions predominantly rely on
predefined patterns or heuristics at the attention head level, struggling to
adapt dynamically to different contexts efficiently.
  We propose SeerAttention, a simple yet effective attention mechanism that
directly learns the block-level attention sparsity from the LLM itself.
Inspired by the gating mechanism in Mixture of Experts (MoE), SeerAttention
augments the conventional attention with a learnable gate that selectively
activates important blocks within the attention map. Specifically, the gate
first pools the query (Q) and key (K) tensors along the sequence dimension and
processes them through learnable linear layers. The resulting matrices are then
multiplied together to produce the gating scores, which are used to predict
block-level attention sparsity. Combined with our block-sparse FlashAttention
kernel, SeerAttention can achieve significant speedup on GPUs. When applied to
pre-trained LLMs, SeerAttention only requires training the gate parameters in a
lightweight self-distillation manner, allowing rapid convergence. Our
evaluation results demonstrate that SeerAttention achieves better model
accuracy and lower latency for long-context pre-filling compared to prior
methods. Code is available at: https://github.com/microsoft/SeerAttention

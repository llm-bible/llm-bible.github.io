---
layout: publication
title: 'Moe-infinity: Efficient Moe Inference On Personal Machines With Sparsity-aware Expert Cache'
authors: Leyang Xue, Yao Fu, Zhan Lu, Luo Mai, Mahesh Marina
conference: "Arxiv"
year: 2024
bibkey: xue2024moe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14361"}
  - {name: "Code", url: "https://github.com/EfficientMoE/MoE-Infinity"}
tags: ['Fine-Tuning', 'RAG', 'Has Code']
---
This paper presents MoE-Infinity, an efficient MoE inference system designed
for personal machines with limited GPU memory capacity. The key idea for
MoE-Infinity is that on personal machines, which are often single-user
environments, MoE-based LLMs typically operate with a batch size of one. In
this setting, MoE models exhibit a high degree of activation sparsity, meaning
a small number of experts are frequently reused in generating tokens during the
decode phase. Leveraging this idea, we design a sparsity-aware expert cache,
which can trace the sparse activation of experts during inference and carefully
select the trace that represents the sparsity pattern. By analyzing these
selected traces, MoE-Infinity guides the replacement and prefetching of the
expert cache, providing 3.1-16.7x per-token latency improvements over numerous
state-of-the-art systems, including vLLM, Ollama, DeepSpeed and BrainStorm
across various MoE models (DeepSeek and Mixtral) when handling different LLM
tasks. MoE-Infinity's source code is publicly available at
https://github.com/EfficientMoE/MoE-Infinity

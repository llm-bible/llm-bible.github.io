---
layout: publication
title: 'Each Rank Could Be An Expert: Single-ranked Mixture Of Experts Lora For Multi-task Learning'
authors: Ziyu Zhao, Yixiao Zhou, Didi Zhu, Tao Shen, Xuwu Wang, Jing Su, Kun Kuang, Zhongyu Wei, Fei Wu, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: zhao2025each
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15103"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization']
---
Low-Rank Adaptation (LoRA) is widely used for adapting large language models
(LLMs) to specific domains due to its efficiency and modularity. Meanwhile,
vanilla LoRA struggles with task conflicts in multi-task scenarios. Recent
works adopt Mixture of Experts (MoE) by treating each LoRA module as an expert,
thereby mitigating task interference through multiple specialized LoRA modules.
While effective, these methods often isolate knowledge within individual tasks,
failing to fully exploit the shared knowledge across related tasks. In this
paper, we establish a connection between single LoRA and multi-LoRA MoE,
integrating them into a unified framework. We demonstrate that the dynamic
routing of multiple LoRAs is functionally equivalent to rank partitioning and
block-level activation within a single LoRA. We further empirically demonstrate
that finer-grained LoRA partitioning, within the same total and activated
parameter constraints, leads to better performance gains across heterogeneous
tasks. Building on these findings, we propose Single-ranked Mixture of Experts
LoRA (\textbf\{SMoRA\}), which embeds MoE into LoRA by \textit\{treating each rank
as an independent expert\}. With a \textit\{dynamic rank-wise activation\}
mechanism, SMoRA promotes finer-grained knowledge sharing while mitigating task
conflicts. Experiments demonstrate that SMoRA activates fewer parameters yet
achieves better performance in multi-task scenarios.

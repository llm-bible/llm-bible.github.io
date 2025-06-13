---
layout: publication
title: 'Moe-lightning: High-throughput Moe Inference On Memory-constrained Gpus'
authors: Shiyi Cao, Shu Liu, Tyler Griggs, Peter Schafhalter, Xiaoxuan Liu, Ying Sheng, Joseph E. Gonzalez, Matei Zaharia, Ion Stoica
conference: "Arxiv"
year: 2024
bibkey: cao2024moe
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.11217'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Model Architecture', 'Tools']
---
Efficient deployment of large language models, particularly Mixture of
Experts (MoE), on resource-constrained platforms presents significant
challenges, especially in terms of computational efficiency and memory
utilization. The MoE architecture, renowned for its ability to increase model
capacity without a proportional increase in inference cost, greatly reduces the
token generation latency compared with dense models. However, the large model
size makes MoE models inaccessible to individuals without high-end GPUs. In
this paper, we propose a high-throughput MoE batch inference system, that
significantly outperforms past work. MoE-Lightning introduces a novel
CPU-GPU-I/O pipelining schedule, CGOPipe, with paged weights to achieve high
resource utilization, and a performance model, HRM, based on a Hierarchical
Roofline Model we introduce to help find policies with higher throughput than
existing systems. MoE-Lightning can achieve up to 10.3x higher throughput than
state-of-the-art offloading-enabled LLM inference systems for Mixtral 8x7B on a
single T4 GPU (16GB). When the theoretical system throughput is bounded by the
GPU memory, MoE-Lightning can reach the throughput upper bound with 2-3x less
CPU memory, significantly increasing resource utilization. MoE-Lightning also
supports efficient batch inference for much larger MoEs (e.g., Mixtral 8x22B
and DBRX) on multiple low-cost GPUs (e.g., 2-4 T4).

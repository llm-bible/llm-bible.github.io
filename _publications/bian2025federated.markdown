---
layout: publication
title: 'Fedalt: Federated Fine-tuning Through Adaptive Local Training With Rest-of-the-world Lora'
authors: Jieming Bian, Lei Wang, Letian Zhang, Jie Xu
conference: "Arxiv"
year: 2025
bibkey: bian2025federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11880"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) in federated settings enables
privacy-preserving adaptation but suffers from cross-client interference due to
model aggregation. Existing federated LoRA fine-tuning methods, primarily based
on FedAvg, struggle with data heterogeneity, leading to harmful cross-client
interference and suboptimal personalization. In this work, we propose
\textbf\{FedALT\}, a novel personalized federated LoRA fine-tuning algorithm that
fundamentally departs from FedAvg. Instead of using an aggregated model to
initialize local training, each client continues training its individual LoRA
while incorporating shared knowledge through a separate Rest-of-the-World
(RoTW) LoRA component. To effectively balance local adaptation and global
information, FedALT introduces an adaptive mixer that dynamically learns
input-specific weightings between the individual and RoTW LoRA components using
the Mixture-of-Experts (MoE) principle. Through extensive experiments on NLP
benchmarks, we demonstrate that FedALT significantly outperforms
state-of-the-art personalized federated LoRA fine-tuning methods, achieving
superior local adaptation without sacrificing computational efficiency.

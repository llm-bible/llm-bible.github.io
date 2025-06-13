---
layout: publication
title: 'Rank Also Matters: Hierarchical Configuration For Mixture Of Adapter Experts In LLM Fine-tuning'
authors: Peizhuang Cong, Wenpu Liu, Wenhan Yu, Haochen Zhao, Tong Yang
conference: "Arxiv"
year: 2025
bibkey: cong2025rank
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03884"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) have demonstrated remarkable success across
various tasks, accompanied by a continuous increase in their parameter size.
Parameter-efficient fine-tuning (PEFT) methods, such as Low-Rank Adaptation
(LoRA), address the challenges of fine-tuning LLMs by significantly reducing
the number of trainable parameters. Recent studies have integrated LoRA with
Mixture of Experts (MoE) architectures, leveraging multiple adapter experts and
gating mechanisms to further improve fine-tuning performance. However, existing
approaches primarily focus on adjusting the allocations of adapter experts per
layer to optimize the introduced trainable parameter size, while neglecting a
critical factor of adapters' rank. To this end, we propose a hierarchical
scheme for expert allocation and rank configuration, HILO, which dynamically
adjusts the number and rank of adapter experts across layers, matching the
varying representational complexity of model layers in adapter-granularity.
Extensive experiments on multiple benchmark tasks demonstrate that HILO
outperforms existing methods in accuracy while introducing fewer trainable
parameters, providing an efficient and practical solution for fine-tuning LLMs.

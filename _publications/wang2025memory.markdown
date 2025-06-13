---
layout: publication
title: 'Memory-efficient LLM Training By Various-grained Low-rank Projection Of Gradients'
authors: Yezhen Wang, Zhouhao Yang, Brian K Chen, Fanyi Pu, Bo Li, Tianyu Gao, Kenji Kawaguchi
conference: "Arxiv"
year: 2025
bibkey: wang2025memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01744"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning']
---
Building upon the success of low-rank adapter (LoRA), low-rank gradient
projection (LoRP) has emerged as a promising solution for memory-efficient
fine-tuning. However, existing LoRP methods typically treat each row of the
gradient matrix as the default projection unit, leaving the role of projection
granularity underexplored. In this work, we propose a novel framework, VLoRP,
that extends low-rank gradient projection by introducing an additional degree
of freedom for controlling the trade-off between memory efficiency and
performance, beyond the rank hyper-parameter. Through this framework, we
systematically explore the impact of projection granularity, demonstrating that
finer-grained projections lead to enhanced stability and efficiency even under
a fixed memory budget. Regarding the optimization for VLoRP, we present
ProjFactor, an adaptive memory-efficient optimizer, that significantly reduces
memory requirement while ensuring competitive performance, even in the presence
of gradient accumulation. Additionally, we provide a theoretical analysis of
VLoRP, demonstrating the descent and convergence of its optimization trajectory
under both SGD and ProjFactor. Extensive experiments are conducted to validate
our findings, covering tasks such as commonsense reasoning, MMLU, and GSM8K.

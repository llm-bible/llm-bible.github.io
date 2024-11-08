---
layout: publication
title: 'Don''t Half-listen: Capturing Key-part Information In Continual Instruction Tuning'
authors: He Yongquan, Huang Xuancheng, Tang Minghao, Meng Lingxun, Li Xiang, Lin Wei, Zhang Wenyuan, Gao Yifu
conference: "Arxiv"
year: 2024
bibkey: he2024half
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10056"}
tags: ['Training Techniques']
---
Instruction tuning for large language models (LLMs) can drive them to produce
results consistent with human goals in specific downstream tasks. However, the
process of continual instruction tuning (CIT) for LLMs may bring about the
catastrophic forgetting (CF) problem, where previously learned abilities are
degraded. Recent methods try to alleviate the CF problem by modifying models or
replaying data, which may only remember the surface-level pattern of
instructions and get confused on held-out tasks. In this paper, we propose a
novel continual instruction tuning method based on Key-part Information Gain
(KPIG). Our method computes the information gain on masked parts to dynamically
replay data and refine the training objective, which enables LLMs to capture
task-aware information relevant to the correct response and alleviate
overfitting to general descriptions in instructions. In addition, we propose
two metrics, P-score and V-score, to measure the generalization and
instruction-following abilities of LLMs. Experiments demonstrate our method
achieves superior performance on both seen and held-out tasks.

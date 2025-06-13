---
layout: publication
title: 'MAIN: Mutual Alignment Is Necessary For Instruction Tuning'
authors: Fanyi Yang, Jianfeng Liu, Xin Zhang, Haoyu Liu, Xixin Cao, Yuefeng Zhan, Hao Sun, Weiwei Deng, Feng Sun, Qi Zhang
conference: "Arxiv"
year: 2025
bibkey: yang2025mutual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12913'}
tags: ['Reinforcement Learning', 'Tools']
---
Instruction tuning has enabled large language models (LLMs) to achieve
remarkable performance, but its success heavily depends on the availability of
large-scale, high-quality instruction-response pairs. However, current methods
for scaling up data generation often overlook a crucial aspect: the alignment
between instructions and responses. We hypothesize that high-quality
instruction-response pairs are not defined by the individual quality of each
component, but by the extent of their alignment with each other. To address
this, we propose a Mutual Alignment Framework (MAIN) that ensures coherence
between the instruction and response through mutual constraints. Experiments
demonstrate that models such as LLaMA and Mistral, fine-tuned within this
framework, outperform traditional methods across multiple benchmarks. This
approach underscores the critical role of instruction-response alignment in
enabling scalable and high-quality instruction tuning for LLMs.

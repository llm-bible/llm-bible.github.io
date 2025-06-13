---
layout: publication
title: 'Optimize Weight Rounding Via Signed Gradient Descent For The Quantization Of Llms'
authors: Wenhua Cheng, Weiwei Zhang, Haihao Shen, Yiyang Cai, Xin He, Kaokao Lv, Yi Liu
conference: "Arxiv"
year: 2023
bibkey: cheng2023optimize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05516"}
  - {name: "Code", url: "https://github.com/intel/auto-round"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Quantization', 'Has Code']
---
Large Language Models (LLMs) have demonstrated exceptional proficiency in
language-related tasks, but their deployment poses significant challenges due
to substantial memory and storage requirements. Weight-only quantization has
emerged as a promising solution, significantly reducing memory and storage
needs without sacrificing too much performance. In this study, we introduce
SignRound, a method that leverages signed gradient descent (SignSGD) to
optimize rounding values and weight clipping in just 200 steps. SignRound
integrates the advantages of Quantization-Aware Training (QAT) and
Post-Training Quantization (PTQ), delivering exceptional results across 2 to 4
bits while minimizing tuning costs and avoiding additional inference overhead.
For example, SignRound achieved absolute average accuracy improvements ranging
from 6.91% to 33.22% at 2bits, as measured by the average zero-shot accuracy
across 11 tasks. It also demonstrates strong generalization in recent models,
achieving near-lossless 4-bit quantization in most scenarios. The source code
is publicly available at https://github.com/intel/auto-round.

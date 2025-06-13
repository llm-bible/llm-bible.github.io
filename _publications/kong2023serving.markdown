---
layout: publication
title: 'Swapmoe: Serving Off-the-shelf Moe-based Large Language Models With Tunable Memory Budget'
authors: Rui Kong, Yuanchun Li, Qingtian Feng, Weijun Wang, Xiaozhou Ye, Ye Ouyang, Linghe Kong, Yunxin Liu
conference: "Arxiv"
year: 2023
bibkey: kong2023serving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15030"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Pruning', 'Pretraining Methods', 'Transformer', 'Applications']
---
Mixture of experts (MoE) is a popular technique to improve capacity of Large
Language Models (LLMs) with conditionally-activated parallel experts. However,
serving MoE models on memory-constrained devices is challenging due to the
large parameter size. Typical solutions such as memory swapping or expert
pruning may lead to significantly higher latency or severe accuracy loss. In
this paper, we introduce SwapMoE, a framework for efficient serving of
MoE-based large language models with tunable memory budgets. The main idea of
SwapMoE is to keep a small dynamic set of important experts, namely Virtual
Experts, in the main memory for inference, while seamlessly maintaining how the
Virtual Experts map to the actual experts. Experiments have shown that SwapMoE
can reduce the memory footprint while maintaining reasonable accuracy. For
example, on text summarization tasks with Switch Transformer, SwapMoE can
reduce the memory consumption from 14.2 GiB to 4.7 GiB, together with 50%
latency reduction and a slight Rouge-2 score drop of 0.041.

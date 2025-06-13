---
layout: publication
title: 'A Deeper Look At Depth Pruning Of Llms'
authors: Shoaib Ahmed Siddiqui, Xin Dong, Greg Heinrich, Thomas Breuel, Jan Kautz, David Krueger, Pavlo Molchanov
conference: "Arxiv"
year: 2024
bibkey: siddiqui2024deeper
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16286"}
tags: ['Transformer', 'Efficiency and Optimization', 'Ethics and Bias', 'Pruning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism']
---
Large Language Models (LLMs) are not only resource-intensive to train but
even more costly to deploy in production. Therefore, recent work has attempted
to prune blocks of LLMs based on cheap proxies for estimating block importance,
effectively removing 10% of blocks in well-trained LLaMa-2 and Mistral 7b
models without any significant degradation of downstream metrics. In this
paper, we explore different block importance metrics by considering adaptive
metrics such as Shapley value in addition to static ones explored in prior
work. We show that adaptive metrics exhibit a trade-off in performance between
tasks i.e., improvement on one task may degrade performance on the other due to
differences in the computed block influences. Furthermore, we extend this
analysis from a complete block to individual self-attention and feed-forward
layers, highlighting the propensity of the self-attention layers to be more
amendable to pruning, even allowing removal of upto 33% of the self-attention
layers without incurring any performance degradation on MMLU for Mistral 7b
(significant reduction in costly maintenance of KV-cache). Finally, we look at
simple performance recovery techniques to emulate the pruned layers by training
lightweight additive bias or low-rank linear adapters. Performance recovery
using emulated updates avoids performance degradation for the initial blocks
(up to 5% absolute improvement on MMLU), which is either competitive or
superior to the learning-based technique.

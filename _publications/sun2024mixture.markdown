---
layout: publication
title: 'Mixture Of Diverse Size Experts'
authors: Manxi Sun, Wei Liu, Jian Luan, Pengzhi Gao, Bin Wang
conference: "Arxiv"
year: 2024
bibkey: sun2024mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.12210'}
tags: ['Training Techniques', 'Model Architecture']
---
The Sparsely-Activated Mixture-of-Experts (MoE) has gained increasing
popularity for scaling up large language models (LLMs) without exploding
computational costs. Despite its success, the current design faces a challenge
where all experts have the same size, limiting the ability of tokens to choose
the experts with the most appropriate size for generating the next token. In
this paper, we propose the Mixture of Diverse Size Experts (MoDSE), a new MoE
architecture with layers designed to have experts of different sizes. Our
analysis of difficult token generation tasks shows that experts of various
sizes achieve better predictions, and the routing path of the experts tends to
be stable after a training period. However, having experts of diverse sizes can
lead to uneven workload distribution. To tackle this limitation, we introduce
an expert-pair allocation strategy to evenly distribute the workload across
multiple GPUs. Comprehensive evaluations across multiple benchmarks demonstrate
the effectiveness of MoDSE, as it outperforms existing MoEs by allocating the
parameter budget to experts adaptively while maintaining the same total
parameter size and the number of experts.

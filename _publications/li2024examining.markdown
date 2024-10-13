---
layout: publication
title: 'Examining Post-training Quantization For Mixture-of-experts: A Benchmark'
authors: Li Pingzhi, Jin Xiaolong, Cheng Yu, Chen Tianlong
conference: "Arxiv"
year: 2024
bibkey: li2024examining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08155"}
tags: ['Efficiency And Optimization', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models~(LLMs) have become foundational in the realm of natural
language processing, demonstrating performance improvements as model sizes
increase. The Mixture-of-Experts~(MoE) approach offers a promising way to scale
LLMs more efficiently by using fewer computational FLOPs through sparse
activation. However, it suffers from significant memory overheads,
necessitating model compression techniques. Post-training quantization, a
popular method for model compression, proves less effective when directly
applied to MoE models due to MoE's overlooked inherent sparsity. This paper
explores several MoE structure-aware quantization heuristics, ranging from
coarse to fine granularity, from MoE block to individual linear weight. Our
investigations reveal critical principles: different MoE structures (i.e.,
blocks, experts, linear layers) require varying numbers of weight bits for
effective and efficient quantization. Conclusions are supported by extensive
benchmarking across two representative MoE models and six tasks. We further
introduce novel enhancements to more accurately identify the most critical
weights in MoE quantization that necessitate higher bit allocations, including
the linear weight outlier scorer and MoE block scorer. Additionally, subsequent
experiments validate our findings in the context of both weight and activation
quantization.

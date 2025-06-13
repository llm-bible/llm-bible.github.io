---
layout: publication
title: 'Automixq: Self-adjusting Quantization For High Performance Memory-efficient Fine-tuning'
authors: Changhai Zhou, Shiyang Zhang, Yuhua Zhou, Zekai Liu, Shichao Weng
conference: "Arxiv"
year: 2024
bibkey: zhou2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13814"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pruning', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) under resource constraints is a
significant challenge in deep learning. Low-Rank Adaptation (LoRA), pruning,
and quantization are all effective methods for improving resource efficiency.
However, combining them directly often results in suboptimal performance,
especially with uniform quantization across all model layers. This is due to
the complex, uneven interlayer relationships introduced by pruning,
necessitating more refined quantization strategies. To address this, we propose
AutoMixQ, an end-to-end optimization framework that selects optimal
quantization configurations for each LLM layer. AutoMixQ leverages lightweight
performance models to guide the selection process, significantly reducing time
and computational resources compared to exhaustive search methods. By
incorporating Pareto optimality, AutoMixQ balances memory usage and
performance, approaching the upper bounds of model capability under strict
resource constraints. Our experiments on widely used benchmarks show that
AutoMixQ reduces memory consumption while achieving superior performance. For
example, at a 30% pruning rate in LLaMA-7B, AutoMixQ achieved 66.21% on BoolQ
compared to 62.45% for LoRA and 58.96% for LoftQ, while reducing memory
consumption by 35.5% compared to LoRA and 27.5% compared to LoftQ.

---
layout: publication
title: 'Neuromorphic Principles For Efficient Large Language Models On Intel Loihi 2'
authors: Steven Abreu, Sumit Bam Shrestha, Rui-jie Zhu, Jason Eshraghian
conference: "Arxiv"
year: 2025
bibkey: abreu2025neuromorphic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18002"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Transformer']
---
Large language models (LLMs) deliver impressive performance but require large
amounts of energy. In this work, we present a MatMul-free LLM architecture
adapted for Intel's neuromorphic processor, Loihi 2. Our approach leverages
Loihi 2's support for low-precision, event-driven computation and stateful
processing. Our hardware-aware quantized model on GPU demonstrates that a 370M
parameter MatMul-free model can be quantized with no accuracy loss. Based on
preliminary results, we report up to 3x higher throughput with 2x less energy,
compared to transformer-based LLMs on an edge GPU, with significantly better
scaling. Further hardware optimizations will increase throughput and decrease
energy consumption. These results show the potential of neuromorphic hardware
for efficient inference and pave the way for efficient reasoning models capable
of generating complex, long-form text rapidly and cost-effectively.

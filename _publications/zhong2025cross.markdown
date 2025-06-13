---
layout: publication
title: 'Cross-attention Speculative Decoding'
authors: Wei Zhong, Manasa Bharadwaj, Yixiao Wang, Nikhil Verma, Yipeng Ji, Chul Lee
conference: "Arxiv"
year: 2025
bibkey: zhong2025cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24544"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Speculative decoding (SD) is a widely adopted approach for accelerating inference in large language models (LLMs), particularly when the draft and target models are well aligned. However, state-of-the-art SD methods typically rely on tightly coupled, self-attention-based Transformer decoders, often augmented with auxiliary pooling or fusion layers. This coupling makes them increasingly complex and harder to generalize across different models. We present Budget EAGLE (Beagle), the first, to our knowledge, cross-attention-based Transformer decoder SD model that achieves performance on par with leading self-attention SD models (EAGLE-v2) while eliminating the need for pooling or auxiliary components, simplifying the architecture, improving training efficiency, and maintaining stable memory usage during training-time simulation. To enable effective training of this novel architecture, we propose Two-Stage Block-Attention Training, a new method that achieves training stability and convergence efficiency in block-level attention scenarios. Extensive experiments across multiple LLMs and datasets show that Beagle achieves competitive inference speedups and higher training efficiency than EAGLE-v2, offering a strong alternative for architectures in speculative decoding.

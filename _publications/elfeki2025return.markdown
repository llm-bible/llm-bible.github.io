---
layout: publication
title: 'Return Of The Encoder: Maximizing Parameter Efficiency For Slms'
authors: Mohamed Elfeki, Rui Liu, Chad Voegele
conference: "Arxiv"
year: 2025
bibkey: elfeki2025return
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.16273'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'Applications', 'Reinforcement Learning']
---
The dominance of large decoder-only language models has overshadowed
encoder-decoder architectures, despite their fundamental efficiency advantages
in sequence processing. For small language models (SLMs) - those with 1 billion
parameters or fewer - our systematic analysis across GPU, CPU, and NPU
platforms reveals that encoder-decoder architectures achieve 47% lower
first-token latency and 4.7x higher throughput compared to decoder-only models
on edge devices. These gains may be attributed to encoder-decoder's one-time
input processing and efficient separation of understanding and generation
phases.
  We introduce a novel knowledge distillation framework that enables
encoder-decoder models to leverage capabilities from large scalable
decoder-only teachers while preserving their architectural advantages,
achieving up to 6 average performance points improvement across diverse tasks,
with significant gains in asymmetric sequence tasks where input and output
distributions can benefit from different processing approaches.
  When combined with modern advances like Rotary Positional Embeddings (RoPE)
and Vision encoders, our systematic investigation demonstrates that
encoder-decoder architectures provide a more practical path toward deploying
capable language models in resource-constrained environments. Our findings
challenge the prevailing trend toward decoder-only scaling, showing that
architectural choices become increasingly crucial as parameter budgets
decrease, particularly for on-device and edge deployments where computational
efficiency is paramount.

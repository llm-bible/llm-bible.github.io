---
layout: publication
title: 'Hybrid-level Instruction Injection For Video Token Compression In Multi-modal Large Language Models'
authors: Zhihang Liu, Chen-wei Xie, Pandeng Li, Liming Zhao, Longxiang Tang, Yun Zheng, Chuanbin Liu, Hongtao Xie
conference: "Arxiv"
year: 2025
bibkey: liu2025hybrid
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16036'}
  - {name: "Code", url: 'https://github.com/lntzm/HICom'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Pre-Training']
---
Recent Multi-modal Large Language Models (MLLMs) have been challenged by the
computational overhead resulting from massive video frames, often alleviated
through compression strategies. However, the visual content is not equally
contributed to user instructions, existing strategies (\eg, average pool)
inevitably lead to the loss of potentially useful information. To tackle this,
we propose the Hybrid-level Instruction Injection Strategy for Conditional
Token Compression in MLLMs (HICom), utilizing the instruction as a condition to
guide the compression from both local and global levels. This encourages the
compression to retain the maximum amount of user-focused information while
reducing visual tokens to minimize computational burden. Specifically, the
instruction condition is injected into the grouped visual tokens at the local
level and the learnable tokens at the global level, and we conduct the
attention mechanism to complete the conditional compression. From the
hybrid-level compression, the instruction-relevant visual parts are highlighted
while the temporal-spatial structure is also preserved for easier understanding
of LLMs. To further unleash the potential of HICom, we introduce a new
conditional pre-training stage with our proposed dataset HICom-248K.
Experiments show that our HICom can obtain distinguished video understanding
ability with fewer tokens, increasing the performance by 2.43% average on
three multiple-choice QA benchmarks and saving 78.8% tokens compared with the
SOTA method. The code is available at https://github.com/lntzm/HICom.

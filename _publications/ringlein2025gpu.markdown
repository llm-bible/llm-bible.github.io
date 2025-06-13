---
layout: publication
title: 'GPU Performance Portability Needs Autotuning'
authors: Burkhard Ringlein, Thomas Parnell, Radu Stoica
conference: "Arxiv"
year: 2025
bibkey: ringlein2025gpu
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03780'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Model Architecture', 'Tools']
---
As LLMs grow in complexity, achieving state-of-the-art performance requires tight co-design across algorithms, software, and hardware. Today's reliance on a single dominant platform limits portability, creates vendor lock-in, and raises barriers for new AI hardware. In this work, we make the case for combining just-in-time (JIT) compilation with kernel parameter autotuning to enable portable LLM inference with state-of-the-art performance without code changes. Focusing on flash attention -- a widespread performance critical LLM kernel -- we demonstrate that this approach explores up to 15x more kernel parameter configurations, produces significantly more diverse code across multiple dimensions, and even outperforms vendor-optimized implementations by up to 230%, all while reducing kernel code size by 70x and eliminating manual code optimizations. Our results highlight autotuning as a promising path to unlocking model portability across GPU vendors.

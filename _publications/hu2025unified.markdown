---
layout: publication
title: 'Tokenflex: Unified VLM Training For Flexible Visual Tokens Inference'
authors: Junshan Hu, Jialiang Mao, Zhikang Liu, Zhongpu Xia, Peng Jia, Xianpeng Lang
conference: "Arxiv"
year: 2025
bibkey: hu2025unified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.03154'}
tags: ['RAG', 'Multimodal Models', 'Training Techniques', 'Tools']
---
Conventional Vision-Language Models(VLMs) typically utilize a fixed number of
vision tokens, regardless of task complexity. This one-size-fits-all strategy
introduces notable inefficiencies: using excessive tokens leads to unnecessary
computational overhead in simpler tasks, whereas insufficient tokens compromise
fine-grained visual comprehension in more complex contexts. To overcome these
limitations, we present TokenFLEX, an innovative and adaptable vision-language
framework that encodes images into a variable number of tokens for efficient
integration with a Large Language Model (LLM). Our approach is underpinned by
two pivotal innovations. Firstly, we present a novel training paradigm that
enhances performance across varying numbers of vision tokens by stochastically
modulating token counts during training. Secondly, we design a lightweight
vision token projector incorporating an adaptive pooling layer and SwiGLU,
allowing for flexible downsampling of vision tokens and adaptive selection of
features tailored to specific token counts. Comprehensive experiments reveal
that TokenFLEX consistently outperforms its fixed-token counterparts, achieving
notable performance gains across various token counts enhancements of 1.6%,
1.0%, and 0.4% with 64, 144, and 256 tokens, respectively averaged over eight
vision-language benchmarks. These results underscore TokenFLEX's remarkable
flexibility while maintaining high-performance vision-language understanding.

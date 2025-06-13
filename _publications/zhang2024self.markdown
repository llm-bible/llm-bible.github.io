---
layout: publication
title: 'SLED: Self Logits Evolution Decoding For Improving Factuality In Large Language Models'
authors: Jianyi Zhang, Da-cheng Juan, Cyrus Rashtchian, Chun-sung Ferng, Heinrich Jiang, Yiran Chen
conference: "Arxiv"
year: 2024
bibkey: zhang2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02433'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable capabilities, but
their outputs can sometimes be unreliable or factually incorrect. To address
this, we introduce Self Logits Evolution Decoding (SLED), a novel decoding
framework that enhances the truthfulness of LLMs without relying on external
knowledge bases or requiring further fine-tuning. From an optimization
perspective, our SLED framework leverages the latent knowledge embedded within
the LLM by contrasting the output logits from the final layer with those from
early layers. It then utilizes an approximate gradient approach to enable
latent knowledge to guide the self-refinement of outputs, thereby effectively
improving factual accuracy. Extensive experiments have been conducted on
established benchmarks across a diverse range of model families (LLaMA 2, LLaMA
3, Gemma) and scales (from 2B to 70B), including more advanced architectural
configurations such as the mixture of experts (MoE). Our evaluation spans a
wide variety of tasks, including multi-choice, open-generation, and adaptations
to chain-of-thought reasoning tasks. The results demonstrate that SLED
consistently improves factual accuracy by up to 20% compared to existing
decoding methods while maintaining natural language fluency and negligible
latency overhead. Furthermore, it can be flexibly combined with other decoding
methods to further enhance their performance.

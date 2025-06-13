---
layout: publication
title: 'Specextend: A Drop-in Enhancement For Speculative Decoding Of Long Sequences'
authors: Jungyoub Cha, Hyunjong Kim, Sungzoon Cho
conference: "Arxiv"
year: 2025
bibkey: cha2025drop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20776"}
  - {name: "Code", url: "https://github.com/jycha98/SpecExtend"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code']
---
Speculative decoding is a widely adopted technique for accelerating inference in large language models (LLMs), but its performance degrades on long inputs due to increased attention cost and reduced draft accuracy. We introduce SpecExtend, a drop-in enhancement that improves the performance of speculative decoding on long sequences without any additional training. SpecExtend integrates efficient attention mechanisms such as FlashAttention and Hybrid Tree Attention into both the draft and target models, reducing latency across all stages. To improve draft accuracy and speed, we propose Cross-model Retrieval, a novel KV cache update strategy that uses the target model's attention scores to dynamically select relevant context for the draft model. Extensive evaluations on three long-context understanding datasets show that SpecExtend accelerates standard tree-based speculative decoding by up to 2.22x for inputs up to 16K tokens, providing an effective solution for speculative decoding of long sequences. The code is available at https://github.com/jycha98/SpecExtend .

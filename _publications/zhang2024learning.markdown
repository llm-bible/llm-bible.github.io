---
layout: publication
title: 'Learning Harmonized Representations For Speculative Sampling'
authors: Lefan Zhang, Xiaodan Wang, Yanhua Huang, Ruiwen Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15766"}
  - {name: "Code", url: "https://github.com/HArmonizedSS/HASS"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Distillation', 'Has Code']
---
Speculative sampling is a promising approach to accelerate the decoding stage
for Large Language Models (LLMs). Recent advancements that leverage target
LLM's contextual information, such as hidden states and KV cache, have shown
significant practical improvements. However, these approaches suffer from
inconsistent context between training and decoding. We also observe another
discrepancy between the training and decoding objectives in existing
speculative sampling methods. In this work, we propose a solution named
HArmonized Speculative Sampling (HASS) that learns harmonized representations
to address these issues. HASS accelerates the decoding stage without adding
inference overhead through harmonized objective distillation and harmonized
context alignment. Experiments on four LLaMA models demonstrate that HASS
achieves 2.81x-4.05x wall-clock time speedup ratio averaging across three
datasets, surpassing EAGLE-2 by 8%-20%. The code is available at
https://github.com/HArmonizedSS/HASS.

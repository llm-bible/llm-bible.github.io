---
layout: publication
title: Scissorhands Exploiting the Persistence of Importance Hypothesis for LLM KV Cache Compression at Test Time
authors: Liu Zichang, Desai Aditya, Liao Fangshuo, Wang Weitao, Xie Victor, Xu Zhaozhuo, Kyrillidis Anastasios, Shrivastava Anshumali
conference: "Arxiv"
year: 2023
bibkey: liu2023scissorhands
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17118"}
tags: ['ARXIV', 'Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'LLM', 'Quantization', 'Tools']
---
Large language models(LLMs) have sparked a new wave of exciting AI applications. Hosting these models at scale requires significant memory resources. One crucial memory bottleneck for the deployment stems from the context window. It is commonly recognized that model weights are memory hungry; however the size of key-value embedding stored during the generation process (KV cache) can easily surpass the model size. The enormous size of the KV cache puts constraints on the inference batch size which is crucial for high throughput inference workload. Inspired by an interesting observation of the attention scores we hypothesize the persistence of importance only pivotal tokens which had a substantial influence at one step will significantly influence future generations. Based on our empirical verification and theoretical analysis around this hypothesis we propose Scissorhands a system that maintains the memory usage of the KV cache at a fixed budget without finetuning the model. In essence Scissorhands manages the KV cache by storing the pivotal tokens with a higher probability. We validate that Scissorhands reduces the inference memory usage of the KV cache by up to 5X without compromising model quality. We further demonstrate that Scissorhands can be combined with 4-bit quantization traditionally used to compress model weights to achieve up to 20X compression.

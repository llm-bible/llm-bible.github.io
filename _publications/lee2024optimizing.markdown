---
layout: publication
title: 'LRQ: Optimizing Post-training Quantization For Large Language Models By Learning Low-rank Weight-scaling Matrices'
authors: Lee Jung Hyun, Kim Jeonghoon, Yang June Yong, Kwon Se Jung, Yang Eunho, Yoo Kang Min, Lee Dongsoo
conference: "Arxiv"
year: 2024
bibkey: lee2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11534"}
  - {name: "Code", url: "https://github.com/onliwad101/FlexRound_LRQ"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
With the commercialization of large language models (LLMs), weight-activation
quantization has emerged to compress and accelerate LLMs, achieving high
throughput while reducing inference costs. However, existing post-training
quantization (PTQ) techniques for quantizing weights and activations of LLMs
still suffer from non-negligible accuracy drops, especially on massive
multitask language understanding. To address this issue, we propose Low-Rank
Quantization (LRQ) \\(-\\) a simple yet effective post-training weight quantization
method for LLMs that reconstructs the outputs of an intermediate Transformer
block by leveraging low-rank weight-scaling matrices, replacing the
conventional full weight-scaling matrices that entail as many learnable scales
as their associated weights. Thanks to parameter sharing via low-rank
structure, LRQ only needs to learn significantly fewer parameters while
enabling the individual scaling of weights, thus boosting the generalization
capability of quantized LLMs. We show the superiority of LRQ over prior LLM PTQ
works under (i) \\(8\\)-bit weight and per-tensor activation quantization, (ii)
\\(4\\)-bit weight and \\(8\\)-bit per-token activation quantization, and (iii) low-bit
weight-only quantization schemes. Our code is available at
\url\{https://github.com/onliwad101/FlexRound_LRQ\} to inspire LLM researchers
and engineers.

---
layout: publication
title: 'PARD: Accelerating LLM Inference With Low-cost Parallel Draft Model Adaptation'
authors: Zihao An, Huajun Bai, Ziqiong Liu, Dong Li, Emad Barsoum
conference: "Arxiv"
year: 2025
bibkey: an2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18583"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
The autoregressive nature of large language models (LLMs) limits inference
speed. Each forward pass generates only a single token and is often
bottlenecked by memory bandwidth. Speculative decoding alleviates this issue
using a draft-then-verify approach to accelerate token generation. However, the
overhead introduced during the draft phase and the training cost of the draft
model limit the efficiency and adaptability of speculative decoding. In this
work, we introduce PARallel Draft (PARD), a novel speculative decoding method
that enables low-cost adaptation of autoregressive draft models into parallel
draft models. PARD enhances inference efficiency by predicting multiple future
tokens in a single forward pass of the draft phase, and incorporates a
conditional drop token method to accelerate training. Its target-independence
property allows a single draft model to be applied to an entire family of
different models, minimizing the adaptation cost. Our proposed conditional drop
token method can improves draft model training efficiency by 3x. On our
optimized inference framework, PARD accelerates LLaMA3.1-8B inference by 4.08x,
achieving 311.5 tokens per second.

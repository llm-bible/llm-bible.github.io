---
layout: publication
title: 'Over-reasoning And Redundant Calculation Of Large Language Models'
authors: Cheng-han Chiang, Hung-yi Lee
conference: "Arxiv"
year: 2024
bibkey: chiang2024over
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.11467'}
  - {name: "Code", url: 'https://github.com/d223302/Over-Reasoning-of-LLMs'}
tags: ['Has Code', 'Uncategorized']
---
Large language models (LLMs) can solve problems step-by-step. While this
chain-of-thought (CoT) reasoning boosts LLMs' performance, it is unclear if
LLMs \textit\{know\} when to use CoT and whether those CoT are always necessary
to answer the question. This paper shows that LLMs tend to generate redundant
calculations and reasoning on a manually constructed math QA dataset,
GSM8K-Zero. GSM8K-Zero is constructed such that the questions can be answered
without any calculations, but LLMs, including Llama-2 models and Claude-2, tend
to generate lengthy and unnecessary calculations to answer the questions. We
also conduct experiments to explain why LLMs generate redundant calculations
and reasonings. GSM8K-Zero is publicly available at
https://github.com/d223302/Over-Reasoning-of-LLMs and
https://huggingface.co/datasets/dcml0714/GSM8K-Zero.

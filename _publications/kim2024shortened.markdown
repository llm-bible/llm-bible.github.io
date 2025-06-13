---
layout: publication
title: 'Shortened Llama: Depth Pruning For Large Language Models With Comparison Of Retraining Methods'
authors: Bo-kyeong Kim, Geonmin Kim, Tae-ho Kim, Thibault Castells, Shinkook Choi, Junho Shin, Hyoung-kyu Song
conference: "Arxiv"
year: 2024
bibkey: kim2024shortened
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02834"}
  - {name: "Code", url: "https://github.com/Nota-NetsPresso/shortened-llm"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Pruning', 'Reinforcement Learning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Structured pruning of modern large language models (LLMs) has emerged as a
way of decreasing their high computational needs. Width pruning reduces the
size of projection weight matrices (e.g., by removing attention heads) while
maintaining the number of layers. Depth pruning, in contrast, removes entire
layers or blocks, while keeping the size of the remaining weights unchanged.
Most current research focuses on either width-only or a blend of width and
depth pruning, with little comparative analysis between the two units (width
vs. depth) concerning their impact on LLM inference efficiency. In this work,
we show that simple depth pruning can effectively compress LLMs while achieving
comparable or superior performance to recent width pruning studies. Our pruning
method boosts inference speeds, especially under memory-constrained conditions
that require limited batch sizes for running LLMs, where width pruning is
ineffective. In retraining pruned models for quality recovery, continued
pretraining on a large corpus markedly outperforms LoRA-based tuning,
particularly at severe pruning ratios. We hope this work can help build compact
yet capable LLMs. Code and models can be found at:
https://github.com/Nota-NetsPresso/shortened-llm

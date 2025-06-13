---
layout: publication
title: 'Why Lift So Heavy? Slimming Large Language Models By Cutting Off The Layers'
authors: Shuzhou Yuan, Ercong Nie, Bolei Ma, Michael Färber
conference: "Arxiv"
year: 2024
bibkey: yuan2024why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11700"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Distillation', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs) possess outstanding capabilities in addressing
various natural language processing (NLP) tasks. However, the sheer size of
these models poses challenges in terms of storage, training and inference due
to the inclusion of billions of parameters through layer stacking. While
traditional approaches such as model pruning or distillation offer ways for
reducing model size, they often come at the expense of performance retention.
In our investigation, we systematically explore the approach of reducing the
number of layers in LLMs. Surprisingly, we observe that even with fewer layers,
LLMs maintain similar or better performance levels, particularly in
prompt-based fine-tuning for text classification tasks. Remarkably, in certain
cases, models with a single layer outperform their fully layered counterparts.
These findings offer valuable insights for future work aimed at mitigating the
size constraints of LLMs while preserving their performance, thereby opening
avenues for significantly more efficient use of LLMs.

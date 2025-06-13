---
layout: publication
title: 'Does Training On Synthetic Data Make Models Less Robust?'
authors: Lingze Zhang, Ellie Pavlick
conference: "Arxiv"
year: 2025
bibkey: zhang2025does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07164"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
An increasingly common practice is to train large language models (LLMs)
using synthetic data. Often this synthetic data is produced by the same or
similar LLMs as those it is being used to train. This raises the question of
whether the synthetic data might in fact exacerbate certain "blindspots" by
reinforcing heuristics that the LLM already encodes. In this paper, we conduct
simulated experiments on the natural language inference (NLI) task with
Llama-2-7B-hf models. We use MultiNLI as the general task and HANS, a targeted
evaluation set designed to measure the presence of specific heuristic
strategies for NLI, as our "blindspot" task. Our goal is to determine whether
performance disparities between the general and blind spot tasks emerge. Our
results indicate that synthetic data does not reinforce blindspots in the way
we expected. Specifically, we see that, while fine-tuning with synthetic data
doesn't necessarily reduce the use of the heuristic, it also does not make it
worse as we hypothesized.

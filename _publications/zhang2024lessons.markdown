---
layout: publication
title: 'Snakmodel: Lessons Learned From Training An Open Danish Large Language Model'
authors: Mike Zhang, Max Müller-eberstein, Elisa Bassignana, Rob Van Der Goot
conference: "Arxiv"
year: 2024
bibkey: zhang2024lessons
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12956'}
tags: ['Language Modeling', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training']
---
We present SnakModel, a Danish large language model (LLM) based on Llama2-7B,
which we continuously pre-train on 13.6B Danish words, and further tune on 3.7M
Danish instructions. As best practices for creating LLMs for smaller language
communities have yet to be established, we examine the effects of early
modeling and training decisions on downstream performance throughout the entire
training pipeline, including (1) the creation of a strictly curated corpus of
Danish text from diverse sources; (2) the language modeling and
instruction-tuning training process itself, including the analysis of
intermediate training dynamics, and ablations across different hyperparameters;
(3) an evaluation on eight language and culturally-specific tasks. Across these
experiments SnakModel achieves the highest overall performance, outperforming
multiple contemporary Llama2-7B-based models. By making SnakModel, the majority
of our pre-training corpus, and the associated code available under open
licenses, we hope to foster further research and development in Danish Natural
Language Processing, and establish training guidelines for languages with
similar resource constraints.

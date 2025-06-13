---
layout: publication
title: 'Benchmarking Language Model Creativity: A Case Study On Code Generation'
authors: Yining Lu, Dixuan Wang, Tianjian Li, Dongwei Jiang, Sanjeev Khudanpur, Meng Jiang, Daniel Khashabi
conference: "Arxiv"
year: 2024
bibkey: lu2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09007"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Prompting']
---
As LLMs become increasingly prevalent, it is interesting to consider how
``creative'' these models can be. From cognitive science, creativity consists
of at least two key characteristics: *convergent* thinking (purposefulness
to achieve a given goal) and *divergent* thinking (adaptability to explore
new environments or constraints) \citep\{runco2003critical\}. In this work, we
introduce a framework for quantifying LLM creativity that incorporates the two
design ingredients: (1) We introduce DENIAL PROMPTING which pushes LLMs to
develop more creative solutions to a given problem by incrementally imposing
new constraints on the previous solution, compelling LLMs to adopt new
strategies. (2) We define NEOGAUGE, a metric that quantifies both convergent
and divergent thinking in the generated creative responses by LLMs. We test the
proposed framework on Codeforces problems, which serve as both a natural
dataset for coding tasks and a collection of prior human solutions. We quantify
NEOGAUGE for various proprietary and open-source models and find that even the
most creative model, GPT-4, still falls short of demonstrating human-like
creativity. We also experiment with advanced reasoning strategies (MCTS,
self-correction, etc.) and observe no significant improvement in creativity. As
a by-product of our analysis, we release NEOCODER dataset for reproducing our
results on future models.

---
layout: publication
title: 'Revisiting OPRO: The Limitations Of Small-scale Llms As Optimizers'
authors: Tuo Zhang, Jinyue Yuan, Salman Avestimehr
conference: "ACL Findings 2024"
year: 2024
bibkey: zhang2024revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10276"}
tags: ['Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Numerous recent works aim to enhance the efficacy of Large Language Models
(LLMs) through strategic prompting. In particular, the Optimization by
PROmpting (OPRO) approach provides state-of-the-art performance by leveraging
LLMs as optimizers where the optimization task is to find instructions that
maximize the task accuracy. In this paper, we revisit OPRO for automated
prompting with relatively small-scale LLMs, such as LLaMa-2 family and Mistral
7B. Our investigation reveals that OPRO shows limited effectiveness in
small-scale LLMs, with limited inference capabilities constraining optimization
ability. We suggest future automatic prompting engineering to consider both
model capabilities and computational costs. Additionally, for small-scale LLMs,
we recommend direct instructions that clearly outline objectives and
methodologies as robust prompt baselines, ensuring efficient and effective
prompt engineering in ongoing research.

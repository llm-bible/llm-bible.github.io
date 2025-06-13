---
layout: publication
title: 'Should You Use Your Large Language Model To Explore Or Exploit?'
authors: Keegan Harris, Aleksandrs Slivkins
conference: "Arxiv"
year: 2025
bibkey: harris2025should
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00225'}
tags: ['Fine-Tuning', 'Agentic']
---
We evaluate the ability of the current generation of large language models
(LLMs) to help a decision-making agent facing an exploration-exploitation
tradeoff. We use LLMs to explore and exploit in silos in various (contextual)
bandit tasks. We find that while the current LLMs often struggle to exploit,
in-context mitigations may be used to substantially improve performance for
small-scale tasks. However even then, LLMs perform worse than a simple linear
regression. On the other hand, we find that LLMs do help at exploring large
action spaces with inherent semantics, by suggesting suitable candidates to
explore.

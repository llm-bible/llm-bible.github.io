---
layout: publication
title: 'The Lookahead Limitation: Why Multi-operand Addition Is Hard For Llms'
authors: Tanja Baeumel, Josef Van Genabith, Simon Ostermann
conference: "Arxiv"
year: 2025
bibkey: baeumel2025lookahead
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19981'}
tags: ['Reinforcement Learning', 'Tokenization', 'GPT', 'Pretraining Methods']
---
Autoregressive large language models (LLMs) exhibit impressive performance
across various tasks but struggle with simple arithmetic, such as addition of
two or more operands. We show that this struggle arises from LLMs' use of a
simple one-digit lookahead heuristic, which works fairly well (but not perfect)
for two-operand addition but fails in multi-operand cases, where the carry-over
logic is more complex. Our probing experiments and digit-wise accuracy
evaluation show that LLMs fail precisely where a one-digit lookahead is
insufficient to account for cascading carries. We analyze the impact of
tokenization strategies on arithmetic performance and show that all
investigated models, regardless of tokenization, are inherently limited in the
addition of multiple operands due to their reliance on a one-digit lookahead
heuristic. Our findings reveal fundamental limitations that prevent LLMs from
generalizing to more complex numerical reasoning.

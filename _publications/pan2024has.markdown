---
layout: publication
title: '"why" Has The Least Side Effect On Model Editing'
authors: Tsung-hsuan Pan, Chung-chi Chen, Hen-hsen Huang, Hsin-hsi Chen
conference: "Arxiv"
year: 2024
bibkey: pan2024has
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18679"}
tags: ['Training Techniques', 'Reinforcement Learning']
---
Training large language models (LLMs) from scratch is an expensive endeavor,
particularly as world knowledge continually evolves. To maintain relevance and
accuracy of LLMs, model editing has emerged as a pivotal research area. While
these methods hold promise, they can also produce unintended side effects.
Their underlying factors and causes remain largely unexplored. This paper
delves into a critical factor-question type-by categorizing model editing
questions. Our findings reveal that the extent of performance degradation
varies significantly across different question types, providing new insights
for experimental design in knowledge editing. Furthermore, we investigate
whether insights from smaller models can be extrapolated to larger models. Our
results indicate discrepancies in findings between models of different sizes,
suggesting that insights from smaller models may not necessarily apply to
larger models. Additionally, we examine the impact of batch size on side
effects, discovering that increasing the batch size can mitigate performance
drops.

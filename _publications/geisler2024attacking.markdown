---
layout: publication
title: 'Attacking Large Language Models With Projected Gradient Descent'
authors: Simon Geisler, Tom Wollschläger, M. H. I. Abdalla, Johannes Gasteiger, Stephan Günnemann
conference: "Arxiv"
year: 2024
bibkey: geisler2024attacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09154"}
tags: ['Training Techniques', 'Security', 'Efficiency and Optimization', 'Prompting']
---
Current LLM alignment methods are readily broken through specifically crafted
adversarial prompts. While crafting adversarial prompts using discrete
optimization is highly effective, such attacks typically use more than 100,000
LLM calls. This high computational cost makes them unsuitable for, e.g.,
quantitative analyses and adversarial training. To remedy this, we revisit
Projected Gradient Descent (PGD) on the continuously relaxed input prompt.
Although previous attempts with ordinary gradient-based attacks largely failed,
we show that carefully controlling the error introduced by the continuous
relaxation tremendously boosts their efficacy. Our PGD for LLMs is up to one
order of magnitude faster than state-of-the-art discrete optimization to
achieve the same devastating attack results.

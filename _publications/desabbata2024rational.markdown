---
layout: publication
title: 'Rational Metareasoning For Large Language Models'
authors: C. Nicolò De Sabbata, Theodore R. Sumers, Thomas L. Griffiths
conference: "Arxiv"
year: 2024
bibkey: desabbata2024rational
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05563'}
tags: ['Reinforcement Learning', 'Few-Shot', 'Prompting', 'Training Techniques']
---
Being prompted to engage in reasoning has emerged as a core technique for
using large language models (LLMs), deploying additional inference-time compute
to improve task performance. However, as LLMs increase in both size and
adoption, inference costs are correspondingly becoming increasingly burdensome.
How, then, might we optimize reasoning's cost-performance tradeoff? This work
introduces a novel approach based on computational models of metareasoning used
in cognitive science, training LLMs to selectively use intermediate reasoning
steps only when necessary. We first develop a reward function that incorporates
the Value of Computation by penalizing unnecessary reasoning, then use this
reward function with Expert Iteration to train the LLM. Compared to few-shot
chain-of-thought prompting and STaR, our method significantly reduces inference
costs (20-37% fewer tokens generated across three models) while maintaining
task performance across diverse datasets.

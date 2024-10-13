---
layout: publication
title: 'Eliciting The Priors Of Large Language Models Using Iterated In-context Learning'
authors: Zhu Jian-qiao, Griffiths Thomas L.
conference: "Arxiv"
year: 2024
bibkey: zhu2024eliciting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01860"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
As Large Language Models (LLMs) are increasingly deployed in real-world
settings, understanding the knowledge they implicitly use when making decisions
is critical. One way to capture this knowledge is in the form of Bayesian prior
distributions. We develop a prompt-based workflow for eliciting prior
distributions from LLMs. Our approach is based on iterated learning, a Markov
chain Monte Carlo method in which successive inferences are chained in a way
that supports sampling from the prior distribution. We validated our method in
settings where iterated learning has previously been used to estimate the
priors of human participants -- causal learning, proportion estimation, and
predicting everyday quantities. We found that priors elicited from GPT-4
qualitatively align with human priors in these settings. We then used the same
method to elicit priors from GPT-4 for a variety of speculative events, such as
the timing of the development of superhuman AI.

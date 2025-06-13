---
layout: publication
title: 'On Speeding Up Language Model Evaluation'
authors: Jin Peng Zhou, Christian K. Belardi, Ruihan Wu, Travis Zhang, Carla P. Gomes, Wen Sun, Kilian Q. Weinberger
conference: "Arxiv"
year: 2024
bibkey: zhou2024speeding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06172"}
  - {name: "Code", url: "https://github.com/kilian-group/banditeval"}
tags: ['Has Code', 'Prompting', 'Reinforcement Learning']
---
Developing prompt-based methods with Large Language Models (LLMs) requires
making numerous decisions, which give rise to a combinatorial search problem
over hyper-parameters. This exhaustive evaluation can be time-consuming and
costly. In this paper, we propose an \\(\textit\{adaptive\}\\) approach to explore
this space. We are exploiting the fact that often only few samples are needed
to identify clearly superior or inferior settings, and that many evaluation
tests are highly correlated. We lean on multi-armed bandits to sequentially
identify the next (method, validation sample)-pair to evaluate and utilize
low-rank matrix factorization to fill in missing evaluations. We carefully
assess the efficacy of our approach on several competitive benchmark problems
and show that it can identify the top-performing method using only 5-15% of the
typical resources -- resulting in 85-95% LLM cost savings. Our code is
available at https://github.com/kilian-group/banditeval.

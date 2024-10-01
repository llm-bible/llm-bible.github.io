---
layout: publication
title: 'On Speeding Up Language Model Evaluation'
authors: Zhou Jin Peng, Belardi Christian K., Wu Ruihan, Zhang Travis, Gomes Carla P., Sun Wen, Weinberger Kilian Q.
conference: "Arxiv"
year: 2024
bibkey: zhou2024speeding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06172"}
tags: ['Pretraining Methods', 'Prompting']
---
'Developing prompt-based methods with Large Language Models (LLMs) requires making numerous decisions, which give rise to a combinatorial search problem. For example, selecting the right pre-trained LLM, prompt, and hyperparameters to attain the best performance for a task typically necessitates evaluating an expoential number of candidates on large validation sets. This exhaustive evaluation can be time-consuming and costly, as both inference and evaluation of LLM-based approaches are resource-intensive. Worse, a lot of computation is wasted: Many hyper-parameter settings are non-competitive, and many samples from the validation set are highly correlated - providing little or no new information. So, if the goal is to identify the best method, it can be done far more efficiently if the validation samples and methods are selected adaptively. In this paper, we propose a novel method to address this challenge. We lean on low-rank matrix factorization to fill in missing evaluations and on multi-armed bandits to sequentially identify the next (method, validation sample)-pair to evaluate. We carefully assess the efficacy of our approach on several competitive benchmark problems and show that it can identify the top-performing method using only 5-15&#37; of the typically needed resources -- resulting in a staggering 85-95&#37; LLM cost savings.'

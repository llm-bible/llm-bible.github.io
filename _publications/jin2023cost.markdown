---
layout: publication
title: 'The Cost Of Down-scaling Language Models: Fact Recall Deteriorates Before In-context Learning'
authors: Tian Jin, Nolan Clement, Xin Dong, Vaishnavh Nagarajan, Michael Carbin, Jonathan Ragan-kelley, Gintare Karolina Dziugaite
conference: "Arxiv"
year: 2023
bibkey: jin2023cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04680"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pruning', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
How does scaling the number of parameters in large language models (LLMs)
affect their core capabilities? We study two natural scaling techniques --
weight pruning and simply training a smaller or larger model, which we refer to
as dense scaling -- and their effects on two core capabilities of LLMs: (a)
recalling facts presented during pre-training and (b) processing information
presented in-context during inference. By curating a suite of tasks that help
disentangle these two capabilities, we find a striking difference in how these
two abilities evolve due to scaling. Reducing the model size by more than 30%
(via either scaling approach) significantly decreases the ability to recall
facts seen in pre-training. Yet, a 60--70% reduction largely preserves the
various ways the model can process in-context information, ranging from
retrieving answers from a long context to learning parameterized functions from
in-context exemplars. The fact that both dense scaling and weight pruning
exhibit this behavior suggests that scaling model size has an inherently
disparate effect on fact recall and in-context learning.

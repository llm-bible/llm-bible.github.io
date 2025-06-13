---
layout: publication
title: 'Language Model Prompt Selection Via Simulation Optimization'
authors: Haoting Zhang, Jinghai He, Rhonda Righter, Zeyu Zheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08164"}
tags: ['Tools', 'Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Prompting']
---
With the advancement in generative language models, the selection of prompts
has gained significant attention in recent years. A prompt is an instruction or
description provided by the user, serving as a guide for the generative
language model in content generation. Despite existing methods for prompt
selection that are based on human labor, we consider facilitating this
selection through simulation optimization, aiming to maximize a pre-defined
score for the selected prompt. Specifically, we propose a two-stage framework.
In the first stage, we determine a feasible set of prompts in sufficient
numbers, where each prompt is represented by a moderate-dimensional vector. In
the subsequent stage for evaluation and selection, we construct a surrogate
model of the score regarding the moderate-dimensional vectors that represent
the prompts. We propose sequentially selecting the prompt for evaluation based
on this constructed surrogate model. We prove the consistency of the sequential
evaluation procedure in our framework. We also conduct numerical experiments to
demonstrate the efficacy of our proposed framework, providing practical
instructions for implementation.

---
layout: publication
title: "Improving Activation Steering In Language Models With Mean-centring"
authors: Jorgensen Ole, Cope Dylan, Schoots Nandi, Shanahan Murray
conference: "Arxiv"
year: 2023
bibkey: jorgensen2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03813"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
Recent work in activation steering has demonstrated the potential to better control the outputs of Large Language Models (LLMs) but it involves finding steering vectors. This is difficult because engineers do not typically know how features are represented in these models. We seek to address this issue by applying the idea of mean-centring to steering vectors. We find that taking the average of activations associated with a target dataset and then subtracting the mean of all training activations results in effective steering vectors. We test this method on a variety of models on natural language tasks by steering away from generating toxic text and steering the completion of a story towards a target genre. We also apply mean-centring to extract function vectors more effectively triggering the execution of a range of natural language tasks by a significant margin (compared to previous baselines). This suggests that mean-centring can be used to easily improve the effectiveness of activation steering in a wide range of contexts.

---
layout: publication
title: COPAL Continual Pruning in Large Language Generative Models
authors: Malla Srikanth, Choi Joon Hee, Choi Chiho
conference: "Arxiv"
year: 2024
bibkey: malla2024copal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02347"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pruning', 'Training Techniques']
---
Adapting pre-trained large language models to different domains in natural language processing requires two key considerations high computational demands and models inability to continual adaptation. To simultaneously address both issues this paper presents COPAL (COntinual Pruning in Adaptive Language settings) an algorithm developed for pruning large language generative models under a continual model adaptation setting. While avoiding resource-heavy finetuning or retraining our pruning process is guided by the proposed sensitivity analysis. The sensitivity effectively measures models ability to withstand perturbations introduced by the new dataset and finds models weights that are relevant for all encountered datasets. As a result COPAL allows seamless model adaptation to new domains while enhancing the resource efficiency. Our empirical evaluation on a various size of LLMs show that COPAL outperforms baseline models demonstrating its efficacy in efficiency and adaptability.

---
layout: publication
title: Take The Bull By The Horns Hard Sample45;reweighted Continual Training Improves LLM Generalization
authors: Chen Xuxi, Wang Zhendong, Sow Daouda, Yang Junjie, Chen Tianlong, Liang Yingbin, Zhou Mingyuan, Wang Zhangyang
conference: "Arxiv"
year: 2024
bibkey: chen2024take
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14270"}
  - {name: "Code", url: "https://github.com/VITA&#45;Group/HardFocusTraining"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Has Code', 'Tools', 'Training Techniques']
---
In the rapidly advancing arena of large language models (LLMs) a key challenge is to enhance their capabilities amid a looming shortage of high45;quality training data. Our study starts from an empirical strategy for the light continual training of LLMs using their original pre45;training data sets with a specific focus on selective retention of samples that incur moderately high losses. These samples are deemed informative and beneficial for model refinement contrasting with the highest45;loss samples which would be discarded due to their correlation with data noise and complexity. We then formalize this strategy into a principled framework of Instance45;Reweighted Distributionally Robust Optimization (IR45;DRO). IR45;DRO is designed to dynamically prioritize the training focus on informative samples through an instance reweighting mechanism streamlined by a closed45;form solution for straightforward integration into established training protocols. Through rigorous experimentation with various models and datasets our findings indicate that our sample45;targeted methods significantly improve LLM performance across multiple benchmarks in both continual pre45;training and instruction tuning scenarios. Our codes are available at https://github.com/VITA&#45;Group/HardFocusTraining.

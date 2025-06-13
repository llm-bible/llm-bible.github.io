---
layout: publication
title: 'Bimix: A Bivariate Data Mixing Law For Language Model Pretraining'
authors: Ce Ge, Zhijian Ma, Daoyuan Chen, Yaliang Li, Bolin Ding
conference: "Arxiv"
year: 2024
bibkey: ge2024bivariate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14908"}
tags: ['Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models have demonstrated remarkable capabilities across
various tasks, primarily attributed to the utilization of diversely sourced
data. However, the impact of pretraining data composition on model performance
remains poorly understood. This paper introduces \\(\textbf\{BiMix\}\\), a novel
bivariate data mixing law that models the joint scaling behavior of domain
proportions and data volume in LLM pretraining. \\(\textbf\{BiMix\}\\) provides a
systematic framework for understanding and optimizing data mixtures across
diverse domains. Through extensive experiments on two large-scale datasets, we
demonstrate \\(\textbf\{BiMix\}\\)'s high accuracy in loss extrapolation (mean
relative error < 0.2%) and its generalization to unseen mixtures (R\\(\{\}^\{2\}\\) >
0.97). Optimization of domain proportions yields superior model performance
compared to existing methods. Furthermore, we establish entropy-based measures
as efficient proxies for data mixing, offering a computationally lightweight
strategy. Our work contributes both theoretical insights into data mixing
dynamics and practical tools for enhancing LLM training efficiency, paving the
way for more effective scaling strategies in language model development.

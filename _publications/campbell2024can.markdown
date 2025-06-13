---
layout: publication
title: 'Can Custom Models Learn In-context? An Exploration Of Hybrid Architecture Performance On In-context Learning Tasks'
authors: Ryan Campbell, Nelson Lojo, Kesava Viswanadha, Christoffer Grondal Tryggestad, Derrick Han Sun, Sriteja Vijapurapu, August Rolfsen, Anant Sahai
conference: "Arxiv"
year: 2024
bibkey: campbell2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.03945'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'GPT', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
In-Context Learning (ICL) is a phenomenon where task learning occurs through
a prompt sequence without the necessity of parameter updates. ICL in
Multi-Headed Attention (MHA) with absolute positional embedding has been the
focus of more study than other sequence model varieties. We examine
implications of architectural differences between GPT-2 and LLaMa as well as
LlaMa and Mamba. We extend work done by Garg et al. (2022) and Park et al.
(2024) to GPT-2/LLaMa hybrid and LLaMa/Mamba hybrid models - examining the
interplay between sequence transformation blocks and regressive performance
in-context. We note that certain architectural changes cause degraded training
efficiency/ICL accuracy by converging to suboptimal predictors or converging
slower. We also find certain hybrids showing optimistic performance
improvements, informing potential future ICL-focused architecture
modifications. Additionally, we propose the "ICL regression score", a scalar
metric describing a model's whole performance on a specific task. Compute
limitations impose restrictions on our architecture-space, training duration,
number of training runs, function class complexity, and benchmark complexity.
To foster reproducible and extensible research, we provide a typed, modular,
and extensible Python package on which we run all experiments.

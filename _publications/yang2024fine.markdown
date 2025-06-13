---
layout: publication
title: 'The Fine Line: Navigating Large Language Model Pretraining With Down-streaming Capability Analysis'
authors: Chen Yang, Junzhuo Li, Xinyao Niu, Xinrun Du, Songyang Gao, Haoran Zhang, Zhaoliang Chen, Xingwei Qu, Ruibin Yuan, Yizhi Li, Jiaheng Liu, Stephen W. Huang, Shawn Yue, Ge Zhang
conference: "Arxiv"
year: 2024
bibkey: yang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01204"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Uncovering early-stage metrics that reflect final model performance is one
core principle for large-scale pretraining. The existing scaling law
demonstrates the power-law correlation between pretraining loss and training
flops, which serves as an important indicator of the current training state for
large language models. However, this principle only focuses on the model's
compression properties on the training data, resulting in an inconsistency with
the ability improvements on the downstream tasks. Some follow-up works
attempted to extend the scaling-law to more complex metrics (such as
hyperparameters), but still lacked a comprehensive analysis of the dynamic
differences among various capabilities during pretraining. To address the
aforementioned limitations, this paper undertakes a comprehensive comparison of
model capabilities at various pretraining intermediate checkpoints. Through
this analysis, we confirm that specific downstream metrics exhibit similar
training dynamics across models of different sizes, up to 67 billion
parameters. In addition to our core findings, we've reproduced Amber and
OpenLLaMA, releasing their intermediate checkpoints. This initiative offers
valuable resources to the research community and facilitates the verification
and exploration of LLM pretraining by open-source researchers. Besides, we
provide empirical summaries, including performance comparisons of different
models and capabilities, and tuition of key metrics for different training
phases. Based on these findings, we provide a more user-friendly strategy for
evaluating the optimization state, offering guidance for establishing a stable
pretraining process.

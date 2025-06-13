---
layout: publication
title: 'Spurious Forgetting In Continual Learning Of Language Models'
authors: Junhao Zheng, Xidi Cai, Shengjie Qiu, Qianli Ma
conference: "Arxiv"
year: 2025
bibkey: zheng2025spurious
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13453"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recent advancements in large language models (LLMs) reveal a perplexing
phenomenon in continual learning: despite extensive training, models experience
significant performance declines, raising questions about task alignment and
underlying knowledge retention. This study first explores the concept of
"spurious forgetting", proposing that such performance drops often reflect a
decline in task alignment rather than true knowledge loss. Through controlled
experiments with a synthesized dataset, we investigate the dynamics of model
performance during the initial training phases of new tasks, discovering that
early optimization steps can disrupt previously established task alignments.
Our theoretical analysis connects these shifts to orthogonal updates in model
weights, providing a robust framework for understanding this behavior.
Ultimately, we introduce a Freezing strategy that fix the bottom layers of the
model, leading to substantial improvements in four continual learning
scenarios. Our findings underscore the critical distinction between task
alignment and knowledge retention, paving the way for more effective strategies
in continual learning.

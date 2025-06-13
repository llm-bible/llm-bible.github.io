---
layout: publication
title: 'Integrating Symbolic Execution Into The Fine-tuning Of Code-generating Llms'
authors: Marina Sakharova, Abhinav Anand, Mira Mezini
conference: "Arxiv"
year: 2025
bibkey: sakharova2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15210"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Code-generating Large Language Models (LLMs) have become essential tools in
modern software development, enhancing productivity and accelerating
development. This paper aims to investigate the fine-tuning of code-generating
LLMs using Reinforcement Learning and Direct Preference Optimization, further
improving their performance. To achieve this, we enhance the training data for
the reward model with the help of symbolic execution techniques, ensuring more
comprehensive and objective data. With symbolic execution, we create a custom
dataset that better captures the nuances in code evaluation. Our reward models,
fine-tuned on this dataset, demonstrate significant improvements over the
baseline, CodeRL, in estimating the quality of generated code. Our
code-generating LLMs, trained with the help of reward model feedback, achieve
similar results compared to the CodeRL benchmark.

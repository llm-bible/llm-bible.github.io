---
layout: publication
title: 'On Training Data Influence Of GPT Models'
authors: Yekun Chai, Qingyi Liu, Shuohuan Wang, Yu Sun, Qiwei Peng, Hua Wu
conference: "Arxiv"
year: 2024
bibkey: chai2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07840"}
  - {name: "Code", url: "https://github.com/ernie-research/gptfluence"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Amidst the rapid advancements in generative language models, the
investigation of how training data shapes the performance of GPT models is
still emerging. This paper presents GPTfluence, a novel approach that leverages
a featurized simulation to assess the impact of training examples on the
training dynamics of GPT models. Our approach not only traces the influence of
individual training instances on performance trajectories, such as loss and
other key metrics, on targeted test points but also enables a comprehensive
comparison with existing methods across various training scenarios in GPT
models, ranging from 14 million to 2.8 billion parameters, across a range of
downstream tasks. Contrary to earlier methods that struggle with generalization
to new data, GPTfluence introduces a parameterized simulation of training
dynamics, demonstrating robust generalization capabilities to unseen training
data. This adaptability is evident across both fine-tuning and
instruction-tuning scenarios, spanning tasks in natural language understanding
and generation. We make our code and data publicly available at
https://github.com/ernie-research/gptfluence.

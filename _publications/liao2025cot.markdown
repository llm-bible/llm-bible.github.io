---
layout: publication
title: 'Cot-drive: Efficient Motion Forecasting For Autonomous Driving With Llms And Chain-of-thought Prompting'
authors: Haicheng Liao, Hanlin Kong, Bonan Wang, Chengyue Wang, Wang Ye, Zhengbing He, Chengzhong Xu, Zhenning Li
conference: "Arxiv"
year: 2025
bibkey: liao2025cot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07234"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'Distillation']
---
Accurate motion forecasting is crucial for safe autonomous driving (AD). This
study proposes CoT-Drive, a novel approach that enhances motion forecasting by
leveraging large language models (LLMs) and a chain-of-thought (CoT) prompting
method. We introduce a teacher-student knowledge distillation strategy to
effectively transfer LLMs' advanced scene understanding capabilities to
lightweight language models (LMs), ensuring that CoT-Drive operates in
real-time on edge devices while maintaining comprehensive scene understanding
and generalization capabilities. By leveraging CoT prompting techniques for
LLMs without additional training, CoT-Drive generates semantic annotations that
significantly improve the understanding of complex traffic environments,
thereby boosting the accuracy and robustness of predictions. Additionally, we
present two new scene description datasets, Highway-Text and Urban-Text,
designed for fine-tuning lightweight LMs to generate context-specific semantic
annotations. Comprehensive evaluations of five real-world datasets demonstrate
that CoT-Drive outperforms existing models, highlighting its effectiveness and
efficiency in handling complex traffic scenarios. Overall, this study is the
first to consider the practical application of LLMs in this field. It pioneers
the training and use of a lightweight LLM surrogate for motion forecasting,
setting a new benchmark and showcasing the potential of integrating LLMs into
AD systems.

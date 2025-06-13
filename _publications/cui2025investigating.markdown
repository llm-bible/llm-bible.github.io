---
layout: publication
title: 'Investigating The Zone Of Proximal Development Of Language Models For In-context Learning'
authors: Peng Cui, Mrinmaya Sachan
conference: "Arxiv"
year: 2025
bibkey: cui2025investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06990'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
In this paper, we introduce a learning analytics framework to analyze the
in-context learning (ICL) behavior of large language models (LLMs) through the
lens of the Zone of Proximal Development (ZPD), an established theory in
educational psychology. ZPD delineates the space between what a learner is
capable of doing unsupported and what the learner cannot do even with support.
We adapt this concept to ICL, measuring the ZPD of LLMs based on model
performance on individual examples with and without ICL. Furthermore, we
propose an item response theory (IRT) model to predict the distribution of
zones for LLMs. Our findings reveal a series of intricate and multifaceted
behaviors of ICL, providing new insights into understanding and leveraging this
technique. Finally, we demonstrate how our framework can enhance LLM in both
inference and fine-tuning scenarios: (1) By predicting a model's zone of
proximal development, we selectively apply ICL to queries that are most likely
to benefit from demonstrations, achieving a better balance between inference
cost and performance; (2) We propose a human-like curriculum for fine-tuning,
which prioritizes examples within the model's ZPD. The curriculum results in
improved performance, and we explain its effectiveness through an analysis of
the training dynamics of LLMs.

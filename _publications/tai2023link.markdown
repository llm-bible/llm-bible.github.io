---
layout: publication
title: Link45;context Learning For Multimodal Llms
authors: Tai Yan, Fan Weichen, Zhang Zhao, Zhu Feng, Zhao Rui, Liu Ziwei
conference: "Arxiv"
year: 2023
bibkey: tai2023link
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07891"}
  - {name: "Code", url: "https://github.com/isekai&#45;portal/Link&#45;Context&#45;Learning"}
tags: ['Has Code', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The ability to learn from context with novel concepts and deliver appropriate responses are essential in human conversations. Despite current Multimodal Large Language Models (MLLMs) and Large Language Models (LLMs) being trained on mega45;scale datasets recognizing unseen images or understanding novel concepts in a training45;free manner remains a challenge. In45;Context Learning (ICL) explores training45;free few45;shot learning where models are encouraged to learn to learn from limited tasks and generalize to unseen tasks. In this work we propose link45;context learning (LCL) which emphasizes reasoning from cause and effect to augment the learning capabilities of MLLMs. LCL goes beyond traditional ICL by explicitly strengthening the causal relationship between the support set and the query set. By providing demonstrations with causal links LCL guides the model to discern not only the analogy but also the underlying causal associations between data points which empowers MLLMs to recognize unseen images and understand novel concepts more effectively. To facilitate the evaluation of this novel approach we introduce the ISEKAI dataset comprising exclusively of unseen generated image45;label pairs designed for link45;context learning. Extensive experiments show that our LCL45;MLLM exhibits strong link45;context learning capabilities to novel concepts over vanilla MLLMs. Code and data will be released at https://github.com/isekai&#45;portal/Link&#45;Context&#45;Learning.

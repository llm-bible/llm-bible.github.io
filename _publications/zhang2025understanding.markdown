---
layout: publication
title: 'Understanding The Generalization Of In-context Learning In Transformers: An Empirical Study'
authors: Xingxuan Zhang, Haoran Wang, Jiansheng Li, Yuan Xue, Shikai Guan, Renzhe Xu, Hao Zou, Han Yu, Peng Cui
conference: "Arxiv"
year: 2025
bibkey: zhang2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.15579'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'GPT', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Large language models (LLMs) like GPT-4 and LLaMA-3 utilize the powerful
in-context learning (ICL) capability of Transformer architecture to learn on
the fly from limited examples. While ICL underpins many LLM applications, its
full potential remains hindered by a limited understanding of its
generalization boundaries and vulnerabilities. We present a systematic
investigation of transformers' generalization capability with ICL relative to
training data coverage by defining a task-centric framework along three
dimensions: inter-problem, intra-problem, and intra-task generalization.
Through extensive simulation and real-world experiments, encompassing tasks
such as function fitting, API calling, and translation, we find that
transformers lack inter-problem generalization with ICL, but excel in
intra-task and intra-problem generalization. When the training data includes a
greater variety of mixed tasks, it significantly enhances the generalization
ability of ICL on unseen tasks and even on known simple tasks. This guides us
in designing training data to maximize the diversity of tasks covered and to
combine different tasks whenever possible, rather than solely focusing on the
target task for testing.

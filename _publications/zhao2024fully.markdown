---
layout: publication
title: '7B Fully Open Source Moxin-llm -- From Pretraining To Grpo-based Reinforcement Learning Enhancement'
authors: Pu Zhao, Xuan Shen, Zhenglun Kong, Yixin Shen, Sung-en Chang, Timothy Rupprecht, Lei Lu, Enfu Nan, Changdi Yang, Yumei He, Weiyan Shi, Xingchen Xu, Yu Huang, Wei Jiang, Wei Wang, Yue Chen, Yong He, Yanzhi Wang
conference: "Arxiv"
year: 2024
bibkey: zhao2024fully
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06845'}
tags: ['Attention Mechanism', 'Agentic', 'Ethics and Bias', 'Few-Shot', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Training Techniques', 'GPT', 'Reinforcement Learning', 'Pre-Training', 'Interpretability', 'Responsible AI', 'Pretraining Methods']
---
Recently, Large Language Models (LLMs) have undergone a significant
transformation, marked by a rapid rise in both their popularity and
capabilities. Leading this evolution are proprietary LLMs like GPT-4 and
GPT-o1, which have captured widespread attention in the AI community due to
their remarkable performance and versatility. Simultaneously, open-source LLMs,
such as LLaMA, have made great contributions to the ever-increasing popularity
of LLMs due to the ease to customize and deploy the models across diverse
applications. Although open-source LLMs present unprecedented opportunities for
innovation and research, the commercialization of LLMs has raised concerns
about transparency, reproducibility, and safety. Many open-source LLMs fail to
meet fundamental transparency requirements by withholding essential components
like training code and data, which may hinder further innovations on LLMs. To
mitigate this issue, we introduce Moxin 7B, a fully open-source LLM developed,
adhering to principles of open science, open source, open data, and open
access. We release the pre-training code and configurations, training and
fine-tuning datasets, and intermediate and final checkpoints, aiming to make
continuous commitments to fully open-source LLMs. After pre-training and
obtaining the base model, we finetune the Moxin Base model with SOTA
post-training framework and instruction data to obtain Moxin Instruct model. To
improve the reasoning capability, we further finetune our Instruct model with
chain-of-thought data distilled from DeepSeek R1, and then use Group Relative
Policy Optimization (GRPO), an efficient and effective reinforcement learning
algorithm following DeepSeek R1, to finetune our model, leading to the Moxin
Reasoning model. Experiments show that our models achieve superior performance
in various evaluations such as zero-shot evaluation, few-shot evaluation, and
CoT evaluation.

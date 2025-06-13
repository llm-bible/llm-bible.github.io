---
layout: publication
title: 'Redefining Machine Translation On Social Network Services With Large Language Models'
authors: Hongcheng Guo, Fei Zhao, Shaosheng Cao, Xinze Lyu, Ziyan Liu, Yue Wang, Boyang Wang, Zhoujun Li, Chonggang Lu, Zhe Xu, Yao Hu
conference: "Arxiv"
year: 2025
bibkey: guo2025redefining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07901"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning']
---
The globalization of social interactions has heightened the need for machine
translation (MT) on Social Network Services (SNS), yet traditional models
struggle with culturally nuanced content like memes, slang, and pop culture
references. While large language models (LLMs) have advanced general-purpose
translation, their performance on SNS-specific content remains limited due to
insufficient specialized training data and evaluation benchmarks. This paper
introduces RedTrans, a 72B LLM tailored for SNS translation, trained on a novel
dataset developed through three innovations: (1) Supervised Finetuning with
Dual-LLM Back-Translation Sampling, an unsupervised sampling method using
LLM-based back-translation to select diverse data for large-scale finetuning;
(2) Rewritten Preference Optimization (RePO), an algorithm that identifies and
corrects erroneous preference pairs through expert annotation, building
reliable preference corpora; and (3) RedTrans-Bench, the first benchmark for
SNS translation, evaluating phenomena like humor localization, emoji semantics,
and meme adaptation. Experiments show RedTrans outperforms state-of-the-art
LLMs. Besides, RedTrans has already been deployed in a real-world production
environment, demonstrating that domain-specific adaptation, effectively bridges
the gap between generic and culturally grounded translation systems.

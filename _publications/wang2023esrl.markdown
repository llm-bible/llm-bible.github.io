---
layout: publication
title: ESRL Efficient Sampling-based Reinforcement Learning for Sequence Generation
authors: Wang Chenglong, Zhou Hang, Hu Yimin, Huo Yifu, Li Bei, Liu Tongran, Xiao Tong, Zhu Jingbo
conference: "Arxiv"
year: 2023
bibkey: wang2023esrl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.02223"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Reinforcement Learning', 'Training Techniques']
---
Applying Reinforcement Learning (RL) to sequence generation models enables the direct optimization of long-term rewards ( BLEU and human feedback) but typically requires large-scale sampling over a space of action sequences. This is a computational challenge as presented by the practice of sequence generation problems such as machine translation where we often deal with a large action space ( a vocabulary) and a long action sequence ( a translation). In this work we introduce two-stage sampling and dynamic sampling approaches to improve the sampling efficiency during training sequence generation models via RL. We experiment with our approaches on the traditional sequence generation tasks including machine translation and abstractive summarization. Furthermore we evaluate our approaches in RL from human feedback (RLHF) through training a large language model using the reward model. Experimental results show that the efficient sampling-based RL referred to as ESRL can outperform all baselines in terms of both training efficiency and memory consumption. Notably ESRL yields consistent performance gains over the strong REINFORCE minimum risk training and proximal policy optimization methods.

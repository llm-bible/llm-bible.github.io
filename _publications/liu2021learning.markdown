---
layout: publication
title: Learning To Ask Conversational Questions By Optimizing Levenshtein Distance
authors: Liu Zhongkun, Ren Pengjie, Chen Zhumin, Ren Zhaochun, De Rijke Maarten, Zhou Ming
conference: "Arxiv"
year: 2021
bibkey: liu2021learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.15903"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Conversational Question Simplification (CQS) aims to simplify self45;contained questions into conversational ones by incorporating some conversational characteristics e.g. anaphora and ellipsis. Existing maximum likelihood estimation (MLE) based methods often get trapped in easily learned tokens as all tokens are treated equally during training. In this work we introduce a Reinforcement Iterative Sequence Editing (RISE) framework that optimizes the minimum Levenshtein distance (MLD) through explicit editing actions. RISE is able to pay attention to tokens that are related to conversational characteristics. To train RISE we devise an Iterative Reinforce Training (IRT) algorithm with a Dynamic Programming based Sampling (DPS) process to improve exploration. Experimental results on two benchmark datasets show that RISE significantly outperforms state45;of45;the45;art methods and generalizes well on unseen data.

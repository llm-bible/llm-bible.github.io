---
layout: publication
title: Neural Machine Translation With Adequacy-oriented Learning
authors: Kong Xiang, Tu Zhaopeng, Shi Shuming, Hovy Eduard, Zhang Tong
conference: "Arxiv"
year: 2018
bibkey: kong2018neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1811.08541"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Although Neural Machine Translation (NMT) models have advanced state-of-the-art performance in machine translation they face problems like the inadequate translation. We attribute this to that the standard Maximum Likelihood Estimation (MLE) cannot judge the real translation quality due to its several limitations. In this work we propose an adequacy-oriented learning mechanism for NMT by casting translation as a stochastic policy in Reinforcement Learning (RL) where the reward is estimated by explicitly measuring translation adequacy. Benefiting from the sequence-level training of RL strategy and a more accurate reward designed specifically for translation our model outperforms multiple strong baselines including (1) standard and coverage-augmented attention models with MLE-based training and (2) advanced reinforcement and adversarial training strategies with rewards based on both word-level BLEU and character-level chrF3. Quantitative and qualitative analyses on different language pairs and NMT architectures demonstrate the effectiveness and universality of the proposed approach.

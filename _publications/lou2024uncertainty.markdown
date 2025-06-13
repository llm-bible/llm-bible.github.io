---
layout: publication
title: 'Uncertainty-aware Reward Model: Teaching Reward Models To Know What Is Unknown'
authors: Xingzhou Lou, Dong Yan, Wei Shen, Yuzi Yan, Jian Xie, Junge Zhang
conference: "Arxiv"
year: 2024
bibkey: lou2024uncertainty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.00847'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization']
---
Reward models (RMs) are essential for aligning large language models (LLM)
with human expectations. However, existing RMs struggle to capture the
stochastic and uncertain nature of human preferences and fail to assess the
reliability of reward predictions. To address these challenges, we introduce
the Uncertainty-aware Reward Model (URM) and its ensemble variant, URME. URM
employs a probabilistic value head to capture aleatoric uncertainty by modeling
the distribution of disentangled human preference attributes. URME further
quantifies epistemic uncertainty by examining discrepancies among individual
URMs within the ensemble, enabling identification of unreliable evaluations.
Our empirical evaluations demonstrate that URM achieves strong performance on
RewardBench, outperforming competitive large-scale models. Additionally,
extensive experiments, including best-of-n sampling (BoN), iterative direct
preference optimization (iterative DPO), and proximal policy optimization
(PPO), demonstrate that URM and URME significantly enhance LLMs' generation
quality. Notably, reward predictions with lower uncertainty are far more
reliable, demonstrate significantly higher quality, and result in substantially
improved alignment.

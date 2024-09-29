---
layout: publication
title: RADE Reference-assisted Dialogue Evaluation For Open-domain Dialogue
authors: Shi Zhengliang, Sun Weiwei, Zhang Shuo, Zhang Zhen, Ren Pengjie, Ren Zhaochun
conference: "Arxiv"
year: 2023
bibkey: shi2023rade
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08156"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Tools']
---
Evaluating open-domain dialogue systems is challenging for reasons such as the one-to-many problem i.e. many appropriate responses other than just the golden response. As of now automatic evaluation methods need better consistency with humans while reliable human evaluation can be time- and cost-intensive. To this end we propose the Reference-Assisted Dialogue Evaluation (RADE) approach under the multi-task learning framework which leverages the pre-created utterance as reference other than the gold response to relief the one-to-many problem. Specifically RADE explicitly compares reference and the candidate response to predict their overall scores. Moreover an auxiliary response generation task enhances prediction via a shared encoder. To support RADE we extend three datasets with additional rated responses other than just a golden response by human annotation. Experiments on our three datasets and two existing benchmarks demonstrate the effectiveness of our method where Pearson Spearman and Kendall correlations with human evaluation outperform state-of-the-art baselines.

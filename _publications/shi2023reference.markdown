---
layout: publication
title: RADE Reference45;assisted Dialogue Evaluation For Open45;domain Dialogue
authors: Shi Zhengliang, Sun Weiwei, Zhang Shuo, Zhang Zhen, Ren Pengjie, Ren Zhaochun
conference: "Arxiv"
year: 2023
bibkey: shi2023reference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08156"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Tools']
---
Evaluating open45;domain dialogue systems is challenging for reasons such as the one45;to45;many problem i.e. many appropriate responses other than just the golden response. As of now automatic evaluation methods need better consistency with humans while reliable human evaluation can be time45; and cost45;intensive. To this end we propose the Reference45;Assisted Dialogue Evaluation (RADE) approach under the multi45;task learning framework which leverages the pre45;created utterance as reference other than the gold response to relief the one45;to45;many problem. Specifically RADE explicitly compares reference and the candidate response to predict their overall scores. Moreover an auxiliary response generation task enhances prediction via a shared encoder. To support RADE we extend three datasets with additional rated responses other than just a golden response by human annotation. Experiments on our three datasets and two existing benchmarks demonstrate the effectiveness of our method where Pearson Spearman and Kendall correlations with human evaluation outperform state45;of45;the45;art baselines.

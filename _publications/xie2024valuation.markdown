---
layout: publication
title: 'Demoshapley: Valuation Of Demonstrations For In-context Learning'
authors: Shan Xie, Man Luo, Chadly Daniel Stern, Mengnan Du, Lu Cheng
conference: "Arxiv"
year: 2024
bibkey: xie2024valuation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07523"}
tags: ['Fine-Tuning', 'Tools', 'Ethics and Bias', 'Bias Mitigation', 'Security', 'Training Techniques', 'Pretraining Methods', 'Fairness', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) using in-context learning (ICL) excel in many tasks without task-specific fine-tuning. However, demonstration selection and ordering greatly impact ICL effectiveness. To address this, we propose DemoShapley and Beta-DemoShapley, inspired by Data Shapley and Beta Shapley, to assess the influence of individual demonstrations. DemoShapley captures how each example influences performance in different contexts, unlike other influence-based methods that rely on a fixed number of demonstrations. Beta-DemoShapley further enhances this framework by incorporating the Beta distribution, allowing users to assign higher weights to smaller cardinalities, which aligns with ICL's prompt length and computational constraints. Our findings show that the proposed algorithms improve model performance by selecting quality demonstrations, and enhancing generalization to out-of-distribution tasks. It also identifies noise-compromised data and promotes fairness in LLMs, protecting model performance and ensuring robustness across various scenarios.

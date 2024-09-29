---
layout: publication
title: -DPO Direct Preference Optimization With Dynamic
authors: Wu Junkang, Xie Yuexiang, Yang Zhengyi, Wu Jiancan, Gao Jinyang, Ding Bolin, Wang Xiang, He Xiangnan
conference: "Arxiv"
year: 2024
bibkey: wu2024direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08639"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Direct Preference Optimization (DPO) has emerged as a compelling approach for training Large Language Models (LLMs) to adhere to human preferences. However the performance of DPO is sensitive to the fine-tuning of its trade-off parameter β as well as to the quality of the preference data. We analyze the impact of β and data quality on DPO uncovering that optimal β values vary with the informativeness of pairwise data. Addressing the limitations of static β values we introduce a novel framework that dynamically calibrates β at the batch level informed by data quality considerations. Additionally our method incorporates β-guided data filtering to safeguard against the influence of outliers. Through empirical evaluation we demonstrate that our dynamic β adjustment technique significantly improves DPOs performance across a range of models and datasets offering a more robust and adaptable training paradigm for aligning LLMs with human feedback. The code is available at .

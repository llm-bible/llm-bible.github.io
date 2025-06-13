---
layout: publication
title: 'Larger Or Smaller Reward Margins To Select Preferences For Alignment?'
authors: Kexin Huang, Junkang Wu, Ziqian Chen, Xue Wang, Jinyang Gao, Bolin Ding, Jiancan Wu, Xiangnan He, Xiang Wang
conference: "Arxiv"
year: 2025
bibkey: huang2025larger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01864"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Preference learning is critical for aligning large language models (LLMs)
with human values, with the quality of preference datasets playing a crucial
role in this process. While existing metrics primarily assess data quality
based on either explicit or implicit reward margins, they often provide
contradictory evaluations for the same data. To address this issue, we
introduce the alignment potential metric, which quantifies the gap from the
model's current implicit reward margin to the target explicit reward margin,
thereby estimating the model's potential to align with the preference data.
Empirical results demonstrate that training on data selected by this metric
consistently enhances alignment performance, surpassing existing metrics across
different base models and optimization objectives. Furthermore, our method
extends to self-play data generation frameworks, where the metric is used to
identify high-quality data within the self-generated content by LLMs. Under
this data generation scenario, our method surpasses current state-of-the-art
(SOTA) results across various training settings and demonstrates continuous
improvements in alignment performance as dataset size and training iterations
increase.

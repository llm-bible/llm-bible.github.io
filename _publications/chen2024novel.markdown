---
layout: publication
title: 'Dlcrec: A Novel Approach For Managing Diversity In Llm-based Recommender Systems'
authors: Jiaju Chen, Chongming Gao, Shuai Yuan, Shuchang Liu, Qingpeng Cai, Peng Jiang
conference: "Arxiv"
year: 2024
bibkey: chen2024novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12470"}
tags: ['Security', 'Training Techniques', 'Tools', 'TACL', 'RecSys', 'Pretraining Methods', 'Fine-Tuning', 'ACL', 'Prompting']
---
The integration of Large Language Models (LLMs) into recommender systems has
led to substantial performance improvements. However, this often comes at the
cost of diminished recommendation diversity, which can negatively impact user
satisfaction. To address this issue, controllable recommendation has emerged as
a promising approach, allowing users to specify their preferences and receive
recommendations that meet their diverse needs. Despite its potential, existing
controllable recommender systems frequently rely on simplistic mechanisms, such
as a single prompt, to regulate diversity-an approach that falls short of
capturing the full complexity of user preferences. In response to these
limitations, we propose DLCRec, a novel framework designed to enable
fine-grained control over diversity in LLM-based recommendations. Unlike
traditional methods, DLCRec adopts a fine-grained task decomposition strategy,
breaking down the recommendation process into three sequential sub-tasks: genre
prediction, genre filling, and item prediction. These sub-tasks are trained
independently and inferred sequentially according to user-defined control
numbers, ensuring more precise control over diversity. Furthermore, the
scarcity and uneven distribution of diversity-related user behavior data pose
significant challenges for fine-tuning. To overcome these obstacles, we
introduce two data augmentation techniques that enhance the model's robustness
to noisy and out-of-distribution data. These techniques expose the model to a
broader range of patterns, improving its adaptability in generating
recommendations with varying levels of diversity. Our extensive empirical
evaluation demonstrates that DLCRec not only provides precise control over
diversity but also outperforms state-of-the-art baselines across multiple
recommendation scenarios.

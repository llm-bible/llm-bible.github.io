---
layout: publication
title: 'Enhancing LLM Reasoning With Iterative DPO: A Comprehensive Empirical Investigation'
authors: Songjun Tu, Jiahao Lin, Xiangyu Tian, Qichao Zhang, Linjing Li, Yuqian Fu, Nan Xu, Wei He, Xiangyuan Lan, Dongmei Jiang, Dongbin Zhao
conference: "Arxiv"
year: 2025
bibkey: tu2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12854"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques']
---
Recent advancements in post-training methodologies for large language models
(LLMs) have highlighted reinforcement learning (RL) as a critical component for
enhancing reasoning. However, the substantial computational costs associated
with RL-based approaches have led to growing interest in alternative paradigms,
such as Direct Preference Optimization (DPO). In this study, we investigate the
effectiveness of DPO in facilitating self-improvement for LLMs through
iterative preference-based learning. We demonstrate that a single round of DPO
with coarse filtering significantly enhances mathematical reasoning
performance, particularly for strong base model. Furthermore, we design an
iterative enhancement framework for both the generator and the reward model
(RM), enabling their mutual improvement through online interaction across
multiple rounds of DPO. Finally, with simple verifiable rewards, our model
DPO-VP achieves RL-level performance with significantly lower computational
overhead. These findings highlight DPO as a scalable and cost-effective
alternative to RL, offering a practical solution for enhancing LLM reasoning in
resource-constrained situations.

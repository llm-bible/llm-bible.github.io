---
layout: publication
title: 'R3HF: Reward Redistribution For Enhancing Reinforcement Learning From Human Feedback'
authors: Jiahui Li, Tai-wei Chang, Fengda Zhang, Kun Kuang, Long Chen
conference: "Arxiv"
year: 2024
bibkey: li2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08302"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning']
---
Reinforcement learning from human feedback (RLHF) provides a paradigm for
aligning large language models (LLMs) with human preferences. This involves the
initial training of a reward model based on pairwise human feedback. The reward
model is subsequently utilized in reinforcement learning to assess the scores
of each generated sentence as a whole, further guiding the optimization of
LLMs. However, current approaches have a significant shortcoming: *They
allocate a single, sparse, and delayed reward to an entire sequence of output*.
This may overlook some significant individual contributions of each token
towards the desired outcome. To overcome this limitation, our paper proposes a
novel reward redistribution method called R3HF, which facilitates a more
fine-grained, token-level reward allocation. Specifically, our method treats
the reward prediction task of the reward model as a regression problem. As a
result, the redistributed rewards are computed by evaluating the specific
contribution of each token to the reward model's output. This detailed approach
improves the model's understanding of language nuances, leading to more precise
enhancements in its performance. Our method is crafted to integrate seamlessly
with most current techniques while incurring minimal computational costs.
Through comprehensive experiments across diverse datasets and tasks, we have
verified the effectiveness and superiority of our approach.

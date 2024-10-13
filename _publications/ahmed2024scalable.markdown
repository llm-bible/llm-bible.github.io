---
layout: publication
title: 'Scalable Ensembling For Mitigating Reward Overoptimisation'
authors: Ahmed Ahmed M., Rafailov Rafael, Sharkov Stepan, Li Xuechen, Koyejo Sanmi
conference: "Arxiv"
year: 2024
bibkey: ahmed2024scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01013"}
tags: ['Agentic', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement Learning from Human Feedback (RLHF) has enabled significant
advancements within language modeling for powerful, instruction-following
models. However, the alignment of these models remains a pressing challenge as
the policy tends to overfit the learned ``proxy" reward model past an
inflection point of utility as measured by a ``gold" reward model that is more
performant -- a phenomenon known as overoptimisation. Prior work has mitigated
this issue by computing a pessimistic statistic over an ensemble of reward
models, which is common in Offline Reinforcement Learning but incredibly costly
for language models with high memory requirements, making such approaches
infeasible for sufficiently large models. To this end, we propose using a
shared encoder but separate linear heads. We find this leads to similar
performance as the full ensemble while allowing tremendous savings in memory
and time required for training for models of similar size.

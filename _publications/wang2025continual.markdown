---
layout: publication
title: 'SEE: Continual Fine-tuning With Sequential Ensemble Of Experts'
authors: Zhilin Wang, Yafu Li, Xiaoye Qu, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: wang2025continual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06664'}
tags: ['Training Techniques', 'Fine-Tuning', 'Tools', 'Pretraining Methods']
---
Continual fine-tuning of large language models (LLMs) suffers from
catastrophic forgetting. Rehearsal-based methods mitigate this problem by
retaining a small set of old data. Nevertheless, they still suffer inevitable
performance loss. Although training separate experts for each task can help
prevent forgetting, effectively assembling them remains a challenge. Some
approaches use routers to assign tasks to experts, but in continual learning,
they often require retraining for optimal performance. To address these
challenges, we introduce the Sequential Ensemble of Experts (SEE) framework.
SEE removes the need for an additional router, allowing each expert to
independently decide whether a query should be handled. The framework employs
distributed routing, and during continual fine-tuning, SEE only requires the
training of new experts for incoming tasks rather than retraining the entire
system. Experiments reveal that the SEE outperforms prior approaches, including
multi-task learning, in continual fine-tuning. It also demonstrates remarkable
generalization ability, as the expert can effectively identify
out-of-distribution queries, which can then be directed to a more generalized
model for resolution. This work highlights the promising potential of
integrating routing and response mechanisms within each expert, paving the way
for the future of distributed model ensembling.

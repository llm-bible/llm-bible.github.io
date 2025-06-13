---
layout: publication
title: 'Ulmrec: User-centric Large Language Model For Sequential Recommendation'
authors: Minglai Shao, Hua Huang, Qiyao Peng, Hongtao Liu
conference: "Arxiv"
year: 2024
bibkey: shao2024user
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.05543'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools', 'Quantization', 'Reinforcement Learning']
---
Recent advances in Large Language Models (LLMs) have demonstrated promising
performance in sequential recommendation tasks, leveraging their superior
language understanding capabilities. However, existing LLM-based recommendation
approaches predominantly focus on modeling item-level co-occurrence patterns
while failing to adequately capture user-level personalized preferences. This
is problematic since even users who display similar behavioral patterns (e.g.,
clicking or purchasing similar items) may have fundamentally different
underlying interests. To alleviate this problem, in this paper, we propose
ULMRec, a framework that effectively integrates user personalized preferences
into LLMs for sequential recommendation. Considering there has the semantic gap
between item IDs and LLMs, we replace item IDs with their corresponding titles
in user historical behaviors, enabling the model to capture the item semantics.
For integrating the user personalized preference, we design two key components:
(1) user indexing: a personalized user indexing mechanism that leverages vector
quantization on user reviews and user IDs to generate meaningful and unique
user representations, and (2) alignment tuning: an alignment-based tuning stage
that employs comprehensive preference alignment tasks to enhance the model's
capability in capturing personalized information. Through this design, ULMRec
achieves deep integration of language semantics with user personalized
preferences, facilitating effective adaptation to recommendation. Extensive
experiments on two public datasets demonstrate that ULMRec significantly
outperforms existing methods, validating the effectiveness of our approach.

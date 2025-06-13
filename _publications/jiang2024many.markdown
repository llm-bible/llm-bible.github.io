---
layout: publication
title: 'Many-shot In-context Learning In Multimodal Foundation Models'
authors: Yixing Jiang, Jeremy Irvin, Ji Hun Wang, Muhammad Ahmed Chaudhry, Jonathan H. Chen, Andrew Y. Ng
conference: "Arxiv"
year: 2024
bibkey: jiang2024many
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.09798'}
  - {name: "Code", url: 'https://github.com/stanfordmlgroup/ManyICL'}
tags: ['Has Code', 'Few-Shot', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'In-Context Learning']
---
Large language models are effective at few-shot in-context learning (ICL).
Recent advancements in multimodal foundation models have enabled
unprecedentedly long context windows, presenting an opportunity to explore
their capability to perform ICL with many more demonstrating examples. In this
work, we evaluate the performance of multimodal foundation models scaling from
few-shot to many-shot ICL. We benchmark GPT-4o and Gemini 1.5 Pro across 14
datasets spanning multiple domains (natural imagery, medical imagery, remote
sensing, and molecular imagery) and tasks (image classification, visual QA, and
object localization). We observe that many-shot ICL, including up to almost
2,000 demonstrating examples, leads to substantial improvements compared to
few-shot (<100 examples) ICL across all of the datasets. Further, Gemini 1.5
Pro performance continues to improve log-linearly up to the maximum number of
tested examples on many datasets. We also find open-weights multimodal
foundation models like Llama 3.2-Vision do not benefit from the demonstrating
examples, highlighting an important gap between open and closed multimodal
foundation models. Given the high inference costs required for many-shot ICL,
we also explore the impact of batching multiple queries in a single API call.
We show that batching up to 50 queries can lead to performance improvements
under zero-shot and many-shot ICL, with substantial gains in the zero-shot
setting on multiple datasets, while drastically reducing per-query cost and
latency. Finally, while GPT-4o and Gemini 1.5 Pro achieve similar zero-shot
performance across the datasets, Gemini 1.5 Pro learns more quickly than GPT-4o
on most datasets. Our results suggest that many-shot ICL could enable users to
efficiently adapt multimodal foundation models to new applications and domains.
Our codebase is publicly available at
https://github.com/stanfordmlgroup/ManyICL .

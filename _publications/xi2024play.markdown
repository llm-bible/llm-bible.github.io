---
layout: publication
title: 'Play To Your Strengths: Collaborative Intelligence Of Conventional Recommender Models And Large Language Models'
authors: Yunjia Xi, Weiwen Liu, Jianghao Lin, Chuhan Wu, Bo Chen, Ruiming Tang, Weinan Zhang, Yong Yu
conference: "Arxiv"
year: 2024
bibkey: xi2024play
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16378"}
tags: ['RecSys', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
The rise of large language models (LLMs) has opened new opportunities in
Recommender Systems (RSs) by enhancing user behavior modeling and content
understanding. However, current approaches that integrate LLMs into RSs solely
utilize either LLM or conventional recommender model (CRM) to generate final
recommendations, without considering which data segments LLM or CRM excel in.
To fill in this gap, we conduct experiments on MovieLens-1M and Amazon-Books
datasets, and compare the performance of a representative CRM (DCNv2) and an
LLM (LLaMA2-7B) on various groups of data samples. Our findings reveal that
LLMs excel in data segments where CRMs exhibit lower confidence and precision,
while samples where CRM excels are relatively challenging for LLM, requiring
substantial training data and a long training time for comparable performance.
This suggests potential synergies in the combination between LLM and CRM.
Motivated by these insights, we propose Collaborative Recommendation with
conventional Recommender and Large Language Model (dubbed \textit\{CoReLLa\}). In
this framework, we first jointly train LLM and CRM and address the issue of
decision boundary shifts through alignment loss. Then, the resource-efficient
CRM, with a shorter inference time, handles simple and moderate samples, while
LLM processes the small subset of challenging samples for CRM. Our experimental
results demonstrate that CoReLLa outperforms state-of-the-art CRM and LLM
methods significantly, underscoring its effectiveness in recommendation tasks.

---
layout: publication
title: 'Learning Item Representations Directly From Multimodal Features For Effective Recommendation'
authors: Xin Zhou, Xiaoxiong Zhang, Dusit Niyato, Zhiqi Shen
conference: "Arxiv"
year: 2025
bibkey: zhou2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04960'}
tags: ['RAG', 'Efficiency and Optimization', 'Merging', 'RecSys', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Conventional multimodal recommender systems predominantly leverage Bayesian
Personalized Ranking (BPR) optimization to learn item representations by
amalgamating item identity (ID) embeddings with multimodal features.
Nevertheless, our empirical and theoretical findings unequivocally demonstrate
a pronounced optimization gradient bias in favor of acquiring representations
from multimodal features over item ID embeddings. As a consequence, item ID
embeddings frequently exhibit suboptimal characteristics despite the
convergence of multimodal feature parameters. Given the rich informational
content inherent in multimodal features, in this paper, we propose a novel
model (i.e., LIRDRec) that learns item representations directly from these
features to augment recommendation performance. Recognizing that features
derived from each modality may capture disparate yet correlated aspects of
items, we propose a multimodal transformation mechanism, integrated with
modality-specific encoders, to effectively fuse features from all modalities.
Moreover, to differentiate the influence of diverse modality types, we devise a
progressive weight copying fusion module within LIRDRec. This module
incrementally learns the weight assigned to each modality in synthesizing the
final user or item representations. Finally, we utilize the powerful visual
understanding of Multimodal Large Language Models (MLLMs) to convert the item
images into texts and extract semantics embeddings upon the texts via LLMs.
Empirical evaluations conducted on five real-world datasets validate the
superiority of our approach relative to competing baselines. It is worth noting
the proposed model, equipped with embeddings extracted from MLLMs and LLMs, can
further improve the recommendation accuracy of NDCG@20 by an average of 4.21%
compared to the original embeddings.

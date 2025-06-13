---
layout: publication
title: 'LLMAEL: Large Language Models Are Good Context Augmenters For Entity Linking'
authors: Amy Xin, Yunjia Qi, Zijun Yao, Fangwei Zhu, Kaisheng Zeng, Xu Bin, Lei Hou, Juanzi Li
conference: "Arxiv"
year: 2024
bibkey: xin2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04020"}
tags: ['RAG', 'Training Techniques']
---
Entity Linking (EL) models are well-trained at mapping mentions to their
corresponding entities according to a given context. However, EL models
struggle to disambiguate long-tail entities due to their limited training data.
Meanwhile, large language models (LLMs) are more robust at interpreting
uncommon mentions. Yet, due to a lack of specialized training, LLMs suffer at
generating correct entity IDs. Furthermore, training an LLM to perform EL is
cost-intensive. Building upon these insights, we introduce LLM-Augmented Entity
Linking LLMAEL, a plug-and-play approach to enhance entity linking through LLM
data augmentation. We leverage LLMs as knowledgeable context augmenters,
generating mention-centered descriptions as additional input, while preserving
traditional EL models for task specific processing. Experiments on 6 standard
datasets show that the vanilla LLMAEL outperforms baseline EL models in most
cases, while the fine-tuned LLMAEL set the new state-of-the-art results across
all 6 benchmarks.

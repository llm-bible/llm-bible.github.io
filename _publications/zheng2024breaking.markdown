---
layout: publication
title: 'Breaking Language Barriers: Cross-lingual Continual Pre-training At Scale'
authors: Zheng Wenzhen, Pan Wenbo, Xu Xu, Qin Libo, Yue Li, Zhou Ming
conference: "Arxiv"
year: 2024
bibkey: zheng2024breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02118"}
tags: ['Pretraining Methods', 'Training Techniques']
---
In recent years, Large Language Models (LLMs) have made significant strides
towards Artificial General Intelligence. However, training these models from
scratch requires substantial computational resources and vast amounts of text
data. In this paper, we explore an alternative approach to constructing an LLM
for a new language by continually pretraining (CPT) from existing pretrained
LLMs, instead of using randomly initialized parameters. Based on parallel
experiments on 40 model sizes ranging from 40M to 5B parameters, we find that
1) CPT converges faster and saves significant resources in a scalable manner;
2) CPT adheres to an extended scaling law derived from Hoffmann et al. (2022)
with a joint data-parameter scaling term; 3) The compute-optimal data-parameter
allocation for CPT markedly differs based on our estimated scaling factors; 4)
The effectiveness of transfer at scale is influenced by training duration and
linguistic properties, while robust to data replaying, a method that
effectively mitigates catastrophic forgetting in CPT. We hope our findings
provide deeper insights into the transferability of LLMs at scale for the
research community.

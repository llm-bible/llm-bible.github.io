---
layout: publication
title: 'Thoughtprobe: Classifier-guided Thought Space Exploration Leveraging LLM Intrinsic Reasoning'
authors: Zijian Wang, Chang Xu
conference: "Arxiv"
year: 2025
bibkey: wang2025classifier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06650"}
tags: ['Fine-Tuning', 'RAG', 'Tools', 'Reinforcement Learning']
---
Pre-trained large language models (LLMs) have been demonstrated to possess
intrinsic reasoning capabilities that can emerge naturally when expanding the
response space. However, the neural representation mechanisms underlying these
intrinsic capabilities and approaches for their optimal utilization remain
inadequately understood. In this work, we make the key discovery that a simple
linear classifier can effectively detect intrinsic reasoning capabilities in
LLMs' activation space, particularly within specific representation types and
network layers. Based on this finding, we propose a classifier-guided search
framework that strategically explore a tree-structured response space. In each
node expansion, the classifier serves as a scoring and ranking mechanism that
efficiently allocates computational resources by identifying and prioritizing
more thoughtful reasoning directions for continuation. After completing the
tree expansion, we collect answers from all branches to form a candidate answer
pool. We propose a branch-aggregation selection method that marginalizes over
all supporting branches by aggregating their thoughtfulness scores, thereby
identifying the optimal answer from the pool. Experimental results show that
our framework's comprehensive exploration not only covers valid reasoning
chains but also effectively identifies them, achieving significant improvements
across multiple arithmetic reasoning benchmarks.

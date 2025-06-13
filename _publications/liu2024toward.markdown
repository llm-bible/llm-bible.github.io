---
layout: publication
title: 'Toward Adaptive Large Language Models Structured Pruning Via Hybrid-grained Weight Importance Assessment'
authors: Jun Liu, Zhenglun Kong, Pu Zhao, Changdi Yang, Hao Tang, Xuan Shen, Geng Yuan, Wei Niu, Wenbin Zhang, Xue Lin, Dong Huang, Yanzhi Wang
conference: "Arxiv"
year: 2024
bibkey: liu2024toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10799"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'Pruning', 'Transformer', 'Attention Mechanism']
---
Structured pruning for large language models (LLMs) has garnered significant
academic interest due to its ability to efficiently compress and accelerate
LLMs by eliminating redundant weight groups at a coarse-grained granularity.
Current structured pruning methods for LLMs typically depend on a singular
granularity for assessing weight importance, resulting in notable performance
degradation in downstream tasks. Intriguingly, our empirical investigations
reveal that utilizing unstructured pruning, which achieves better performance
retention by pruning weights at a finer granularity, *i.e.*, individual
weights, yields significantly varied sparse LLM structures when juxtaposed to
structured pruning. This suggests that evaluating both holistic and individual
assessment for weight importance is essential for LLM pruning. Building on this
insight, we introduce the Hybrid-grained Weight Importance Assessment (HyWIA),
a novel method that merges fine-grained and coarse-grained evaluations of
weight importance for the pruning of LLMs. Leveraging an attention mechanism,
HyWIA adaptively determines the optimal blend of granularity in weight
importance assessments in an end-to-end pruning manner. Extensive experiments
on LLaMA-V1/V2, Vicuna, Baichuan, and Bloom across various benchmarks
demonstrate the effectiveness of HyWIA in pruning LLMs. For example, HyWIA
surpasses the cutting-edge LLM-Pruner by an average margin of 2.82% in accuracy
across seven downstream tasks when pruning LLaMA-7B by 50%.

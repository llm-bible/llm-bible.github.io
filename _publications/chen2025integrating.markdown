---
layout: publication
title: 'Integrating Chain-of-thought For Multimodal Alignment: A Study On 3D Vision-language Learning'
authors: Yanjun Chen, Yirong Sun, Xinghao Chen, Jian Wang, Xiaoyu Shen, Wenjie Li, Wei Zhang
conference: "Arxiv"
year: 2025
bibkey: chen2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06232"}
tags: ['RAG', 'Training Techniques', 'Tools', 'Multimodal Models']
---
Chain-of-Thought (CoT) reasoning has proven effective in natural language
tasks but remains underexplored in multimodal alignment. This study
investigates its integration into 3D vision-language learning by embedding
structured reasoning into alignment training. We introduce the 3D-CoT
Benchmark, a dataset with hierarchical CoT annotations covering shape
recognition, functional inference, and causal reasoning. Through controlled
experiments, we compare CoT-structured and standard textual annotations across
large reasoning models (LRMs) and large language models (LLMs). Our evaluation
employs a dual-layer framework assessing both intermediate reasoning and final
inference quality. Extensive experiments demonstrate that CoT significantly
improves 3D semantic grounding, with LRMs leveraging CoT more effectively than
LLMs. Furthermore, we highlight that annotation structure influences
performance-explicit reasoning markers aid LLMs, while unmarked CoT better
aligns with LRM inference patterns. Our analyses suggest that CoT is crucial
for enhancing multimodal reasoning, with implications beyond 3D tasks. The
dataset will be publicly available at
https://huggingface.co/datasets/Battam/3D-CoT

---
layout: publication
title: 'A Theoretical Understanding Of Chain-of-thought: Coherent Reasoning And Error-aware Demonstration'
authors: Yingqian Cui, Pengfei He, Xianfeng Tang, Qi He, Chen Luo, Jiliang Tang, Yue Xing
conference: "Arxiv"
year: 2024
bibkey: cui2024theoretical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16540"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Few-shot Chain-of-Thought (CoT) prompting has demonstrated strong performance
in improving the reasoning capabilities of large language models (LLMs). While
theoretical investigations have been conducted to understand CoT, the
underlying transformer used in these studies isolates the CoT reasoning process
into separated in-context learning steps (Stepwise ICL). In this work, we
theoretically show that, compared to Stepwise ICL, the transformer gains better
error correction ability and more accurate predictions if the reasoning from
earlier steps (Coherent CoT) is integrated. Given that this coherent reasoning
changes the behavior of the transformer, we further investigate the sensitivity
of the transformer with Coherent CoT when the demonstration examples are
corrupted at the inference stage. Our theoretical results indicate that the
transformer is more sensitive to errors in intermediate reasoning steps than
the final outcome. Building upon this observation, we propose an improvement on
CoT by incorporating both correct and incorrect reasoning paths in the
demonstration. Our experiments validate the effectiveness of the proposed
approach.

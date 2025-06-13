---
layout: publication
title: 'Decoupling Reasoning And Knowledge Injection For In-context Knowledge Editing'
authors: Changyue Wang, Weihang Su, Qingyao Ai, Yujia Zhou, Yiqun Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025decoupling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00536"}
  - {name: "Code", url: "https://github.com/bebr2/DecKER"}
tags: ['Training Techniques', 'Has Code', 'Tools', 'Reinforcement Learning']
---
Knowledge editing aims to efficiently update Large Language Models (LLMs) by modifying specific knowledge without retraining the entire model. Among knowledge editing approaches, in-context editing (ICE) offers a lightweight solution by injecting new knowledge directly into the input context, leaving model parameters unchanged. However, existing ICE approaches do not explicitly separate the newly injected knowledge from the model's original reasoning process. This entanglement often results in conflicts between external updates and internal parametric knowledge, undermining the consistency and accuracy of the reasoning path.In this work, we conduct preliminary experiments to examine how parametric knowledge influences reasoning path planning. We find that the model's reasoning is tightly coupled with its internal knowledge, and that naively injecting new information without adapting the reasoning path often leads to performance degradation, particularly in multi-hop tasks. To this end, we propose DecKER, a novel ICE framework that decouples reasoning from knowledge editing by generating a masked reasoning path and then resolving knowledge edits via hybrid retrieval and model-based validation. Experiments on multi-hop QA benchmarks show that DecKER significantly outperforms existing ICE methods by mitigating knowledge conflicts and preserving reasoning consistency. Our code is available at: https://github.com/bebr2/DecKER .

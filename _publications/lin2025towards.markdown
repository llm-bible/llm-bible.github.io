---
layout: publication
title: 'Towards Automatic Continual Learning: A Self-adaptive Framework For Continual Instruction Tuning'
authors: Peiyi Lin, Fukai Zhang, Kai Niu, Hao Fu
conference: "Arxiv"
year: 2025
bibkey: lin2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15924"}
tags: ['Tools', 'Reinforcement Learning']
---
Continual instruction tuning enables large language models (LLMs) to learn
incrementally while retaining past knowledge, whereas existing methods
primarily focus on how to retain old knowledge rather than on selecting which
new knowledge to learn. In domain-specific contexts, maintaining data quality
and managing system constraints remain key challenges. To address these issues,
we propose an automated continual instruction tuning framework that dynamically
filters incoming data, which identify and reduce redundant data across
successive updates. Our approach utilizes a small proxy model for efficient
perplexity-based filtering, and updates the proxy to ensure that the filtering
criteria remain aligned with the evolving state of the deployed model. Compared
to existing static data selection methods, our framework can effectively handle
incrementally acquired data and shifting distributions. Additionally, it
addresses practical deployment challenges by enabling seamless model updates,
supporting version rollback and incorporating automatic checkpoint evaluation.
We evaluated the system in real-world medical scenarios. It reduced
computational costs by 66.7% and improved model performance, and achieved
autonomous updates, thus demonstrating its effectiveness for automatic
continual instruction tuning.

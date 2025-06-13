---
layout: publication
title: 'Self-consistency Of The Internal Reward Models Improves Self-rewarding Language Models'
authors: Xin Zhou, Yiwen Guo, Ruotian Ma, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2025
bibkey: zhou2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08922"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Applications']
---
Aligning Large Language Models (LLMs) with human preferences is crucial for
their deployment in real-world applications. Recent advancements in
Self-Rewarding Language Models suggest that an LLM can use its internal reward
models (such as LLM-as-a-Judge) \cite\{yuanself\} to generate preference data,
improving alignment performance without costly human annotation. However, we
find that different internal reward models within the same LLM often generate
inconsistent preferences. This inconsistency raises concerns about the
reliability of self-generated preference data, hinders overall alignment
performance, and highlights the need for further research to ensure reliable
and coherent alignment with human preferences. To address this limitation, we
propose Self-Consistent Internal Rewards (SCIR), a novel framework designed to
enhance consistency among internal reward models during training. In each
training step, we collect preference predictions from multiple pre-defined
internal reward models and enforce consistency and confidence through an
inconsistency penalty mechanism, thereby improving the reliability of these
internal reward models. We selectively use data with consistent predictions for
preference optimization, ensuring the quality of the preference data. By
employing self-consistent internal rewards, our method significantly improves
the alignment performance and reward modeling capability of LLMs, outperforming
baseline methods by a notable margin.

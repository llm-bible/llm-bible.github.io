---
layout: publication
title: 'A Practical Memory Injection Attack Against LLM Agents'
authors: Shen Dong, Shaochen Xu, Pengfei He, Yige Li, Jiliang Tang, Tianming Liu, Hui Liu, Zhen Xiang
conference: "Arxiv"
year: 2025
bibkey: dong2025practical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03704'}
tags: ['Agentic', 'Security', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Agents based on large language models (LLMs) have demonstrated strong
capabilities in a wide range of complex, real-world applications. However, LLM
agents with a compromised memory bank may easily produce harmful outputs when
the past records retrieved for demonstration are malicious. In this paper, we
propose a novel Memory INJection Attack, MINJA, that enables the injection of
malicious records into the memory bank by only interacting with the agent via
queries and output observations. These malicious records are designed to elicit
a sequence of malicious reasoning steps leading to undesirable agent actions
when executing the victim user's query. Specifically, we introduce a sequence
of bridging steps to link the victim query to the malicious reasoning steps.
During the injection of the malicious record, we propose an indication prompt
to guide the agent to autonomously generate our designed bridging steps. We
also propose a progressive shortening strategy that gradually removes the
indication prompt, such that the malicious record will be easily retrieved when
processing the victim query comes after. Our extensive experiments across
diverse agents demonstrate the effectiveness of MINJA in compromising agent
memory. With minimal requirements for execution, MINJA enables any user to
influence agent memory, highlighting practical risks of LLM agents.

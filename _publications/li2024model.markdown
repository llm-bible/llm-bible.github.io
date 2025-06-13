---
layout: publication
title: 'Model-editing-based Jailbreak Against Safety-aligned Large Language Models'
authors: Yuxi Li, Zhibo Zhang, Kailong Wang, Ling Shi, Haoyu Wang
conference: "Arxiv"
year: 2024
bibkey: li2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08201"}
tags: ['Responsible AI', 'Security', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG']
---
Large Language Models (LLMs) have transformed numerous fields by enabling
advanced natural language interactions but remain susceptible to critical
vulnerabilities, particularly jailbreak attacks. Current jailbreak techniques,
while effective, often depend on input modifications, making them detectable
and limiting their stealth and scalability. This paper presents Targeted Model
Editing (TME), a novel white-box approach that bypasses safety filters by
minimally altering internal model structures while preserving the model's
intended functionalities. TME identifies and removes safety-critical
transformations (SCTs) embedded in model matrices, enabling malicious queries
to bypass restrictions without input modifications. By analyzing distinct
activation patterns between safe and unsafe queries, TME isolates and
approximates SCTs through an optimization process. Implemented in the D-LLM
framework, our method achieves an average Attack Success Rate (ASR) of 84.86%
on four mainstream open-source LLMs, maintaining high performance. Unlike
existing methods, D-LLM eliminates the need for specific triggers or harmful
response collections, offering a stealthier and more effective jailbreak
strategy. This work reveals a covert and robust threat vector in LLM security
and emphasizes the need for stronger safeguards in model safety alignment.

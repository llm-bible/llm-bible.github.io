---
layout: publication
title: 'AURA: Agentic Upskilling Via Reinforced Abstractions'
authors: Alvin Zhu, Yusuke Tanaka, Dennis Hong
conference: "Arxiv"
year: 2025
bibkey: zhu2025agentic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02507"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting']
---
We study the combinatorial explosion involved in translating high-level task prompts into deployable control policies for agile robots through multi-stage reinforcement learning. We introduce AURA (Agentic Upskilling via Reinforced Abstractions), a schema-centric curriculum RL framework that leverages Large Language Models (LLMs) as autonomous designers of multi-stage curricula. AURA transforms user prompts into YAML workflows that encode full reward functions, domain randomization strategies, and training configurations. All files are statically validated against a schema before any GPU time is consumed, ensuring reliable and efficient execution without human intervention. A retrieval-augmented feedback loop allows specialized LLM agents to design, execute, and refine staged curricula based on prior training results stored in a vector database, supporting continual improvement over time. Ablation studies highlight the importance of retrieval for curriculum quality and convergence stability. Quantitative experiments show that AURA consistently outperforms LLM-guided baselines on GPU-accelerated training frameworks. In qualitative tests, AURA successfully trains end-to-end policies directly from user prompts and deploys them zero-shot on a custom humanoid robot across a range of environments. By abstracting away the complexity of curriculum design, AURA enables scalable and adaptive policy learning pipelines that would be prohibitively complex to construct by hand.

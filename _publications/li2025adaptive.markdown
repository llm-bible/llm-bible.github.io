---
layout: publication
title: 'Selfbudgeter: Adaptive Token Allocation For Efficient LLM Reasoning'
authors: Zheng Li, Qingxiu Dong, Jingyuan Ma, Di Zhang, Zhifang Sui
conference: "Arxiv"
year: 2025
bibkey: li2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11274"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning']
---
Recently, large reasoning models demonstrate exceptional performance on various tasks. However, reasoning models inefficiently over-process both trivial and complex queries, leading to resource waste and prolonged user latency. To address this challenge, we propose SelfBudgeter - a self-adaptive controllable reasoning strategy for efficient reasoning. Our approach adopts a dual-phase training paradigm: first, the model learns to pre-estimate the reasoning cost based on the difficulty of the query. Then, we introduce budget-guided GPRO for reinforcement learning, which effectively maintains accuracy while reducing output length. SelfBudgeter allows users to anticipate generation time and make informed decisions about continuing or interrupting the process. Furthermore, our method enables direct manipulation of reasoning length via pre-filling token budget. Experimental results demonstrate that SelfBudgeter can rationally allocate budgets according to problem complexity, achieving up to 74.47% response length compression on the MATH benchmark while maintaining nearly undiminished accuracy.

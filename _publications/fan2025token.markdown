---
layout: publication
title: 'Cothink: Token-efficient Reasoning Via Instruct Models Guiding Reasoning Models'
authors: Siqi Fan, Peng Han, Shuo Shang, Yequan Wang, Aixin Sun
conference: "Arxiv"
year: 2025
bibkey: fan2025token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.22017'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning']
---
Large language models (LLMs) benefit from increased test-time compute, a phenomenon known as test-time scaling. However, reasoning-optimized models often overthink even simple problems, producing excessively verbose outputs and leading to low token efficiency. By comparing these models with equally sized instruct models, we identify two key causes of this verbosity: (1) reinforcement learning reduces the information density of forward reasoning, and (2) backward chain-of thought training encourages redundant and often unnecessary verification steps. Since LLMs cannot assess the difficulty of a given problem, they tend to apply the same cautious reasoning strategy across all tasks, resulting in inefficient overthinking. To address this, we propose CoThink, an embarrassingly simple pipeline: an instruct model first drafts a high-level solution outline; a reasoning model then works out the solution. We observe that CoThink enables dynamic adjustment of reasoning depth based on input difficulty. Evaluated with three reasoning models DAPO, DeepSeek-R1, and QwQ on three datasets GSM8K, MATH500, and AIME24, CoThink reduces total token generation by 22.3% while maintaining pass@1 accuracy within a 0.42% margin on average. With reference to the instruct model, we formally define reasoning efficiency and observe a potential reasoning efficiency scaling law in LLMs.

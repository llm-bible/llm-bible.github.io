---
layout: publication
title: 'PAFFA: Premeditated Actions For Fast Agents'
authors: Shambhavi Krishna, Zheng Chen, Yuan Ling, Xiaojiang Huang, Yingjie Li, Fan Yang, Xiang Li
conference: "Arxiv"
year: 2024
bibkey: krishna2024premeditated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07958'}
tags: ['Agentic', 'RAG', 'Tools', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning']
---
Modern AI assistants have made significant progress in natural language
understanding and tool-use, with emerging efforts to interact with Web
interfaces. However, current approaches that heavily rely on repeated
LLM-driven HTML parsing are computationally expensive and error-prone,
particularly when handling dynamic web interfaces and multi-step tasks. We
introduce PAFFA (Premeditated Actions For Fast Agents), a method that makes
LLMs faster and more accurate in completing tasks on the internet using a novel
inference-time technique that requires no task-specific training. PAFFA
constructs an 'Action Library', leveraging the parametric knowledge of the base
LLM to pre-compute browser interaction patterns that generalize across tasks.
By strategically re-using LLM inference across tasks - either via 'Dist-Map'
for task-agnostic identification of key interactive web elements, or 'Unravel'
for first-encounter, stateful exploration of novel tasks/sites) - PAFFA
drastically reduces inference time tokens by 87% while maintaining robust
performance (achieving 0.57 vs. 0.50 step accuracy compared to baseline).
Further, Unravel's ability to update its action library based on explorations
allows generalization and adaptation to unseen websites. In sum, this work
exhibits that LLM reasoning sequences can generalize across prompts, offering a
way to scale inference-time techniques for internet-scale data with sublinear
token count.

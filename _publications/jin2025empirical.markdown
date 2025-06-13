---
layout: publication
title: 'An Empirical Study On Reinforcement Learning For Reasoning-search Interleaved LLM Agents'
authors: Bowen Jin, Jinsung Yoon, Priyanka Kargupta, Sercan O. Arik, Jiawei Han
conference: "Arxiv"
year: 2025
bibkey: jin2025empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15117"}
  - {name: "Code", url: "https://github.com/PeterGriffinJin/Search-R1"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Has Code']
---
Reinforcement learning (RL) has demonstrated strong potential in training large language models (LLMs) capable of complex reasoning for real-world problem solving. More recently, RL has been leveraged to create sophisticated LLM-based search agents that adeptly combine reasoning with search engine use. While the use of RL for training search agents is promising, the optimal design of such agents remains not fully understood. In particular, key factors -- such as (1) reward formulation, (2) the choice and characteristics of the underlying LLM, and (3) the role of the search engine in the RL process -- require further investigation. In this work, we conduct comprehensive empirical studies to systematically investigate these and offer actionable insights. We highlight several key findings: format rewards are effective in improving final performance, whereas intermediate retrieval rewards have limited impact; the scale and initialization of the LLM (general-purpose vs. reasoning-specialized) significantly influence RL outcomes; and the choice of search engine plays a critical role in shaping RL training dynamics and the robustness of the trained agent during inference. These establish important guidelines for successfully building and deploying LLM-based search agents in real-world applications. Code is available at https://github.com/PeterGriffinJin/Search-R1.

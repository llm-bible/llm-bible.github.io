---
layout: publication
title: 'Curriculum Guided Reinforcement Learning For Efficient Multi Hop Retrieval Augmented Generation'
authors: Yuelyu Ji, Rui Meng, Zhuochun Li, Daqing He
conference: "Arxiv"
year: 2025
bibkey: ji2025curriculum
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17391'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) grounds large language models (LLMs) in up-to-date external evidence, yet existing multi-hop RAG pipelines still issue redundant subqueries, explore too shallowly, or wander through overly long search chains. We introduce EVO-RAG, a curriculum-guided reinforcement learning framework that evolves a query-rewriting agent from broad early-stage exploration to concise late-stage refinement. EVO-RAG couples a seven-factor, step-level reward vector (covering relevance, redundancy, efficiency, and answer correctness) with a time-varying scheduler that reweights these signals as the episode unfolds. The agent is trained with Direct Preference Optimization over a multi-head reward model, enabling it to learn when to search, backtrack, answer, or refuse. Across four multi-hop QA benchmarks (HotpotQA, 2WikiMultiHopQA, MuSiQue, and Bamboogle), EVO-RAG boosts Exact Match by up to 4.6 points over strong RAG baselines while trimming average retrieval depth by 15 %. Ablation studies confirm the complementary roles of curriculum staging and dynamic reward scheduling. EVO-RAG thus offers a general recipe for building reliable, cost-effective multi-hop RAG systems.

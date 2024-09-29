---
layout: publication
title: "Fidelis: Faithful Reasoning In Large Language Model For Knowledge Graph Question Answering"
authors: Sui Yuan, He Yufei, Liu Nian, He Xiaoxin, Wang Kun, Hooi Bryan
conference: "Arxiv"
year: 2024
bibkey: sui2024faithful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13873"}
tags: ['Applications', 'Fine Tuning', 'RAG', 'Training Techniques']
---
While large language models (LLMs) have achieved significant success in various applications they often struggle with hallucinations especially in scenarios that require deep and responsible reasoning. These issues could be partially mitigate by integrating external knowledge graphs (KG) in LLM reasoning. However the method of their incorporation is still largely unexplored. In this paper we propose a retrieval-exploration interactive method FiDelis to handle intermediate steps of reasoning grounded by KGs. Specifically we propose Path-RAG module for recalling useful intermediate knowledge from KG for LLM reasoning. We incorporate the logic and common-sense reasoning of LLMs and topological connectivity of KGs into the knowledge retrieval process which provides more accurate recalling performance. Furthermore we propose to leverage deductive reasoning capabilities of LLMs as a better criterion to automatically guide the reasoning process in a stepwise and generalizable manner. Deductive verification serve as precise indicators for when to cease further reasoning thus avoiding misleading the chains of reasoning and unnecessary computation. Extensive experiments show that our method as a training-free method with lower computational cost and better generality outperforms the existing strong baselines in three benchmarks.

---
layout: publication
title: 'Reinforced Internal-external Knowledge Synergistic Reasoning For Efficient Adaptive Search Agent'
authors: Ziyang Huang, Xiaowei Yuan, Yiming Ju, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2025
bibkey: huang2025reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07596"}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) is a common strategy to reduce hallucinations in Large Language Models (LLMs). While reinforcement learning (RL) can enable LLMs to act as search agents by activating retrieval capabilities, existing ones often underutilize their internal knowledge. This can lead to redundant retrievals, potential harmful knowledge conflicts, and increased inference latency. To address these limitations, an efficient and adaptive search agent capable of discerning optimal retrieval timing and synergistically integrating parametric (internal) and retrieved (external) knowledge is in urgent need. This paper introduces the Reinforced Internal-External Knowledge Synergistic Reasoning Agent (IKEA), which could indentify its own knowledge boundary and prioritize the utilization of internal knowledge, resorting to external search only when internal knowledge is deemed insufficient. This is achieved using a novel knowledge-boundary aware reward function and a knowledge-boundary aware training dataset. These are designed for internal-external knowledge synergy oriented RL, incentivizing the model to deliver accurate answers, minimize unnecessary retrievals, and encourage appropriate external searches when its own knowledge is lacking. Evaluations across multiple knowledge reasoning tasks demonstrate that IKEA significantly outperforms baseline methods, reduces retrieval frequency significantly, and exhibits robust generalization capabilities.

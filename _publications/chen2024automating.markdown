---
layout: publication
title: Autoprm Automating Procedural Supervision For Multi45;step Reasoning Via Controllable Question Decomposition
authors: Chen Zhaorun, Zhao Zhuokai, Zhu Zhihong, Zhang Ruiqi, Li Xiang, Raj Bhiksha, Yao Huaxiu
conference: "Arxiv"
year: 2024
bibkey: chen2024automating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11452"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools']
---
Recent advancements in large language models (LLMs) have shown promise in multi45;step reasoning tasks yet their reliance on extensive manual labeling to provide procedural feedback remains a significant impediment. To address this challenge in this paper we propose a novel self45;supervised framework AutoPRM that efficiently enhances the fine45;tuning of LLMs for intricate reasoning challenges. Specifically AutoPRM first decomposes complex problems into more manageable subquestions with a controllable granularity switch then sequentially apply reinforcement learning to iteratively improve the subquestion solver. Additionally we propose context45;guided45;decoding to avoid reward tampering and guide the subquestion solver towards the solution of the holistic problem. Extensive experiments show that AutoPRM significantly improves performance on mathematical and commonsense reasoning tasks over SOTA. More encouragingly AutoPRM can be easily integrated with other orthogonal reasoning pipelines.

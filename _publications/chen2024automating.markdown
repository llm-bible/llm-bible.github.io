---
layout: publication
title: 'Autoprm: Automating Procedural Supervision For Multi-step Reasoning Via Controllable Question Decomposition'
authors: Chen Zhaorun, Zhao Zhuokai, Zhu Zhihong, Zhang Ruiqi, Li Xiang, Raj Bhiksha, Yao Huaxiu
conference: "Arxiv"
year: 2024
bibkey: chen2024automating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11452"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent advancements in large language models (LLMs) have shown promise in multi-step reasoning tasks, yet their reliance on extensive manual labeling to provide procedural feedback remains a significant impediment. To address this challenge, in this paper, we propose a novel self-supervised framework AutoPRM that efficiently enhances the fine-tuning of LLMs for intricate reasoning challenges. Specifically, AutoPRM first decomposes complex problems into more manageable subquestions with a controllable granularity switch, then sequentially apply reinforcement learning to iteratively improve the subquestion solver. Additionally, we propose context-guided-decoding to avoid reward tampering and guide the subquestion solver towards the solution of the holistic problem. Extensive experiments show that AutoPRM significantly improves performance on mathematical and commonsense reasoning tasks over SOTA. More encouragingly, AutoPRM can be easily integrated with other orthogonal reasoning pipelines.

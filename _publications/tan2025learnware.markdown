---
layout: publication
title: 'Learnware Of Language Models: Specialized Small Language Models Can Do Big'
authors: Zhi-hao Tan, Zi-chen Zhao, Hao-yu Shi, Xin-yu Zhang, Peng Tan, Yang Yu, Zhi-hua Zhou
conference: "Arxiv"
year: 2025
bibkey: tan2025learnware
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13425'}
tags: ['RAG']
---
The learnware paradigm offers a novel approach to machine learning by enabling users to reuse a set of well-trained models for tasks beyond the models' original purposes. It eliminates the need to build models from scratch, instead relying on specifications (representations of a model's capabilities) to identify and leverage the most suitable models for new tasks. While learnware has proven effective in many scenarios, its application to language models has remained largely unexplored. At the same time, large language models (LLMs) have demonstrated remarkable universal question-answering abilities, yet they face challenges in specialized scenarios due to data scarcity, privacy concerns, and high computational costs, thus more and more specialized small language models (SLMs) are being trained for specific domains. To address these limitations systematically, the learnware paradigm provides a promising solution by enabling maximum utilization of specialized SLMs, and allowing users to identify and reuse them in a collaborative and privacy-preserving manner.
  This paper presents a preliminary attempt to apply the learnware paradigm to language models. We simulated a learnware system comprising approximately 100 learnwares of specialized SLMs with 8B parameters, fine-tuned across finance, healthcare, and mathematics domains. Each learnware contains an SLM and a specification, which enables users to identify the most relevant models without exposing their own data. Experimental results demonstrate promising performance: by selecting one suitable learnware for each task-specific inference, the system outperforms the base SLMs on all benchmarks. Compared to LLMs, the system outperforms Qwen1.5-110B, Qwen2.5-72B, and Llama3.1-70B-Instruct by at least 14% in finance domain tasks, and surpasses Flan-PaLM-540B (ranked 7th on the Open Medical LLM Leaderboard) in medical domain tasks.

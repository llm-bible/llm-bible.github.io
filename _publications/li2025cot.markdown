---
layout: publication
title: 'Cot-rag: Integrating Chain Of Thought And Retrieval-augmented Generation To Enhance Reasoning In Large Language Models'
authors: Feiyang Li, Peng Fang, Zhan Shi, Arijit Khan, Fang Wang, Dan Feng, Weihao Wang, Xin Zhang, Yongjian Cui
conference: "Arxiv"
year: 2025
bibkey: li2025cot
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.13534'}
tags: ['RAG', 'Prompting', 'Applications', 'Tools']
---
Chain-of-thought (CoT) reasoning boosts large language models' (LLMs) performance on complex tasks but faces two key limitations: a lack of reliability when solely relying on LLM-generated reasoning chains and interference from natural language reasoning steps with the models' inference process, also known as the inference logic of LLMs. To address these issues, we propose CoT-RAG, a novel reasoning framework with three key designs: (i) Knowledge Graph-driven CoT Generation,featuring knowledge graphs to modulate reasoning chain generation of LLMs, thereby enhancing reasoning credibility; (ii) Learnable Knowledge Case-aware RAG, which incorporates retrieval-augmented generation (RAG) into knowledge graphs to retrieve relevant sub-cases and sub-descriptions, providing LLMs with learnable information; (iii) Pseudo-Program Prompting Execution, which promotes greater logical rigor by guiding LLMs to execute reasoning tasks as pseudo-programs. Evaluations on nine public datasets spanning three reasoning tasks reveal significant accuracy gains--ranging from 4.0% to 44.3%--over state-of-the-art methods. Furthermore, tests on four domain-specific datasets demonstrate exceptional accuracy and efficient execution, underscoring its practical applicability and scalability.

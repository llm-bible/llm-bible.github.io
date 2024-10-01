---
layout: publication
title: 'Cogmg: Collaborative Augmentation Between Large Language Model And Knowledge Graph'
authors: Zhou Tong, Chen Yubo, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: zhou2024collaborative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17231"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models have become integral to question-answering applications despite their propensity for generating hallucinations and factually inaccurate content. Querying knowledge graphs to reduce hallucinations in LLM meets the challenge of incomplete knowledge coverage in knowledge graphs. On the other hand, updating knowledge graphs by information extraction and knowledge graph completion faces the knowledge update misalignment issue. In this work, we introduce a collaborative augmentation framework, CogMG, leveraging knowledge graphs to address the limitations of LLMs in QA scenarios, explicitly targeting the problems of incomplete knowledge coverage and knowledge update misalignment. The LLMs identify and decompose required knowledge triples that are not present in the KG, enriching them and aligning updates with real-world demands. We demonstrate the efficacy of this approach through a supervised fine-tuned LLM within an agent framework, showing significant improvements in reducing hallucinations and enhancing factual accuracy in QA responses. Our code and video are publicly available.

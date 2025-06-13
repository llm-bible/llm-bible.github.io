---
layout: publication
title: 'Knowledgenavigator: Leveraging Large Language Models For Enhanced Reasoning Over Knowledge Graph'
authors: Tiezheng Guo, Qingwen Yang, Chen Wang, Yanyi Liu, Pan Li, Jiawei Tang, Dapeng Li, Yingyou Wen
conference: "Complex Intelligent Systems (2024) 1-14"
year: 2023
bibkey: guo2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15880"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Large language model (LLM) has achieved outstanding performance on various
downstream tasks with its powerful natural language understanding and zero-shot
capability, but LLM still suffers from knowledge limitation. Especially in
scenarios that require long logical chains or complex reasoning, the
hallucination and knowledge limitation of LLM limit its performance in question
answering (QA). In this paper, we propose a novel framework KnowledgeNavigator
to address these challenges by efficiently and accurately retrieving external
knowledge from knowledge graph and using it as a key factor to enhance LLM
reasoning. Specifically, KnowledgeNavigator first mines and enhances the
potential constraints of the given question to guide the reasoning. Then it
retrieves and filters external knowledge that supports answering through
iterative reasoning on knowledge graph with the guidance of LLM and the
question. Finally, KnowledgeNavigator constructs the structured knowledge into
effective prompts that are friendly to LLM to help its reasoning. We evaluate
KnowledgeNavigator on multiple public KGQA benchmarks, the experiments show the
framework has great effectiveness and generalization, outperforming previous
knowledge graph enhanced LLM methods and is comparable to the fully supervised
models.

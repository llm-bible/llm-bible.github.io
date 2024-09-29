---
layout: publication
title: KnowledgeNavigator Leveraging Large Language Models for Enhanced Reasoning over Knowledge Graph
authors: Guo Tiezheng, Yang Qingwen, Wang Chen, Liu Yanyi, Li Pan, Tang Jiawei, Li Dapeng, Wen Yingyou
conference: "Complex Intelligent Systems"
year: 2023
bibkey: guo2023knowledgenavigator
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15880"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language model (LLM) has achieved outstanding performance on various downstream tasks with its powerful natural language understanding and zero-shot capability but LLM still suffers from knowledge limitation. Especially in scenarios that require long logical chains or complex reasoning the hallucination and knowledge limitation of LLM limit its performance in question answering (QA). In this paper we propose a novel framework KnowledgeNavigator to address these challenges by efficiently and accurately retrieving external knowledge from knowledge graph and using it as a key factor to enhance LLM reasoning. Specifically KnowledgeNavigator first mines and enhances the potential constraints of the given question to guide the reasoning. Then it retrieves and filters external knowledge that supports answering through iterative reasoning on knowledge graph with the guidance of LLM and the question. Finally KnowledgeNavigator constructs the structured knowledge into effective prompts that are friendly to LLM to help its reasoning. We evaluate KnowledgeNavigator on multiple public KGQA benchmarks the experiments show the framework has great effectiveness and generalization outperforming previous knowledge graph enhanced LLM methods and is comparable to the fully supervised models.

---
layout: publication
title: 'Avatar: Optimizing LLM Agents For Tool Usage Via Contrastive Reasoning'
authors: Shirley Wu, Shiyu Zhao, Qian Huang, Kexin Huang, Michihiro Yasunaga, Kaidi Cao, Vassilis N. Ioannidis, Karthik Subbian, Jure Leskovec, James Zou
conference: "Arxiv"
year: 2024
bibkey: wu2024optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11200'}
  - {name: "Code", url: 'https://github.com/zou-group/avatar'}
tags: ['Agentic', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Prompting', 'Multimodal Models']
---
Large language model (LLM) agents have demonstrated impressive capabilities
in utilizing external tools and knowledge to boost accuracy and reduce
hallucinations. However, developing prompting techniques that enable LLM agents
to effectively use these tools and knowledge remains a heuristic and
labor-intensive task. Here, we introduce AvaTaR, a novel and automated
framework that optimizes an LLM agent to effectively leverage provided tools,
improving performance on a given task. During optimization, we design a
comparator module to iteratively deliver insightful and comprehensive prompts
to the LLM agent by contrastively reasoning between positive and negative
examples sampled from training data. We demonstrate AvaTaR on four complex
multimodal retrieval datasets featuring textual, visual, and relational
information, and three general question-answering (QA) datasets. We find AvaTaR
consistently outperforms state-of-the-art approaches across all seven tasks,
exhibiting strong generalization ability when applied to novel cases and
achieving an average relative improvement of 14% on the Hit@1 metric for the
retrieval datasets and 13% for the QA datasets. Code and dataset are available
at https://github.com/zou-group/avatar.

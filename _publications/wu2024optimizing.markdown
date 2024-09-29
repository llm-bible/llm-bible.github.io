---
layout: publication
title: "Avatar: Optimizing LLM Agents For Tool-assisted Knowledge Retrieval"
authors: Wu Shirley, Zhao Shiyu, Huang Qian, Huang Kexin, Yasunaga Michihiro, Cao Kaidi, Ioannidis Vassilis N., Subbian Karthik, Leskovec Jure, Zou James
conference: "Arxiv"
year: 2024
bibkey: wu2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11200"}
  - {name: "Code", url: "https://github.com/zou-group/avatar"}
tags: ['Agentic', 'Efficiency And Optimization', 'Has Code', 'Multimodal Models', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Large language model (LLM) agents have demonstrated impressive capability in utilizing external tools and knowledge to boost accuracy and reduce hallucinations. However developing the prompting techniques that make LLM agents able to effectively use external tools and knowledge is a heuristic and laborious task. Here we introduce AvaTaR a novel and automatic framework that optimizes an LLM agent to effectively use the provided tools and improve its performance on a given task/domain. During optimization we design a comparator module to iteratively provide insightful and holistic prompts to the LLM agent via reasoning between positive and negative examples sampled from training data. We demonstrate AvaTaR on four complex multimodal retrieval datasets featuring textual visual and relational information. We find AvaTaR consistently outperforms state-of-the-art approaches across all four challenging tasks and exhibits strong generalization ability when applied to novel cases achieving an average relative improvement of 1437; on the Hit@1 metric. Code and dataset are available at https://github.com/zou-group/avatar."

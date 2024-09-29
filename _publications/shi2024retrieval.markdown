---
layout: publication
title: Retrieval45;enhanced Knowledge Editing In Language Models For Multi45;hop Question Answering
authors: Shi Yucheng, Tan Qiaoyu, Wu Xuansheng, Zhong Shaochen, Zhou Kaixiong, Liu Ninghao
conference: "Arxiv"
year: 2024
bibkey: shi2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19631"}
  - {name: "Code", url: "https://github.com/sycny/RAE"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Pruning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have shown proficiency in question45;answering tasks but often struggle to integrate real45;time knowledge leading to potentially outdated or inaccurate responses. This problem becomes even more challenging when dealing with multi45;hop questions since they require LLMs to update and integrate multiple knowledge pieces relevant to the questions. To tackle the problem we propose the Retrieval45;Augmented model Editing (RAE) framework for multi45;hop question answering. RAE first retrieves edited facts and then refines the language model through in45;context learning. Specifically our retrieval approach based on mutual information maximization leverages the reasoning abilities of LLMs to identify chain facts that traditional similarity45;based searches might miss. In addition our framework includes a pruning strategy to eliminate redundant information from the retrieved facts which enhances the editing accuracy and mitigates the hallucination problem. Our framework is supported by theoretical justification for its fact retrieval efficacy. Finally comprehensive evaluation across various LLMs validates RAEs ability in providing accurate answers with updated knowledge. Our code is available at https://github.com/sycny/RAE.

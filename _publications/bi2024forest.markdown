---
layout: publication
title: 'Forest-of-thought: Scaling Test-time Compute For Enhancing LLM Reasoning'
authors: Zhenni Bi, Kai Han, Chuanjian Liu, Yehui Tang, Yunhe Wang
conference: "Arxiv"
year: 2024
bibkey: bi2024forest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09078"}
  - {name: "Code", url: "https://github.com/iamhankai/Forest-of-Thought"}
tags: ['Efficiency and Optimization', 'Tools', 'RAG', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable abilities across
various language tasks, but solving complex reasoning problems remains a
significant challenge. While existing methods, such as Chain-of-Thought (CoT)
and Tree-of-Thought (ToT), enhance reasoning by decomposing problems or
structuring prompts, they typically perform a single pass of reasoning and may
fail to revisit flawed paths, compromising accuracy. To address this
limitation, we propose a novel reasoning framework called Forest-of-Thought
(FoT), which integrates multiple reasoning trees to leverage collective
decision-making for solving complex logical problems. FoT employs sparse
activation strategies to select the most relevant reasoning paths, improving
both efficiency and accuracy. Additionally, we introduce a dynamic
self-correction strategy that enables real-time error correction, along with
consensus-guided decision-making strategies to optimize both correctness and
computational resources. Experimental results demonstrate that the FoT
framework, combined with these strategies, significantly enhances the reasoning
capabilities of LLMs, enabling them to solve complex tasks with greater
precision and efficiency. Code will be available at
https://github.com/iamhankai/Forest-of-Thought.

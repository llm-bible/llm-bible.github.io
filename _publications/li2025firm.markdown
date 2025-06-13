---
layout: publication
title: 'Firm Or Fickle? Evaluating Large Language Models Consistency In Sequential Interactions'
authors: Yubo Li, Yidi Miao, Xueying Ding, Ramayya Krishnan, Rema Padman
conference: "Arxiv"
year: 2025
bibkey: li2025firm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.22353'}
  - {name: "Code", url: 'https://github.com/yubol-bobo/MT-Consistency'}
tags: ['Reinforcement Learning', 'Has Code', 'Tools', 'Applications']
---
Large Language Models (LLMs) have shown remarkable capabilities across various tasks, but their deployment in high-stake domains requires consistent and coherent behavior across multiple rounds of user interaction. This paper introduces a comprehensive framework for evaluating and improving LLM response consistency, making three key contributions. Code and data are available at: https://github.com/yubol-bobo/MT-Consistency. First, we introduce Position-Weighted Consistency (PWC), a metric designed to capture both the importance of early-stage stability and recovery patterns in multi-turn interactions. Second, we present MT-Consistency, a carefully curated benchmark dataset spanning diverse domains and difficulty levels, specifically designed to evaluate LLM consistency under various challenging follow-up scenarios. Third, we introduce Confidence-Aware Response Generation (CARG), a framework that significantly improves response stability by explicitly integrating internal model confidence scores during the generation process. Experimental results demonstrate that CARG significantly improves response stability without sacrificing accuracy, offering a practical path toward more dependable LLM behavior in critical, real-world deployments.

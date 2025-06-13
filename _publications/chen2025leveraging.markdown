---
layout: publication
title: 'SETS: Leveraging Self-verification And Self-correction For Improved Test-time Scaling'
authors: Jiefeng Chen, Jie Ren, Xinyun Chen, Chengrun Yang, Ruoxi Sun, Jinsung Yoon, Sercan Ö Arık
conference: "Arxiv"
year: 2025
bibkey: chen2025leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.19306'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Tools']
---
Recent advancements in Large Language Models (LLMs) have created new opportunities to enhance performance on complex reasoning tasks by leveraging test-time computation. However, existing parallel scaling methods, such as repeated sampling or reward model scoring, often suffer from premature convergence and high costs due to task-specific reward model training, while sequential methods like SELF-REFINE cannot effectively leverage increased compute. This paper introduces Self-Enhanced Test-Time Scaling (SETS), a new approach that overcomes these limitations by strategically combining parallel and sequential techniques. SETS exploits the inherent self-verification and self-correction capabilities of LLMs, unifying sampling, verification, and correction within a single framework. This innovative design facilitates efficient and scalable test-time computation for enhanced performance on complex tasks. Our comprehensive experimental results on challenging benchmarks spanning planning, reasoning, math, and coding demonstrate that SETS achieves significant performance improvements and more advantageous test-time scaling behavior than the alternatives.

---
layout: publication
title: 'Deepseek-r1 Vs. O3-mini: How Well Can Reasoning Llms Evaluate MT And Summarization?'
authors: Daniil Larionov, Sotaro Takeshita, Ran Zhang, Yanran Chen, Christoph Leiter, Zhipin Wang, Christian Greisinger, Steffen Eger
conference: "Arxiv"
year: 2025
bibkey: larionov2025deepseek
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08120"}
  - {name: "Code", url: "https://github.com/NL2G/reasoning-eval"}
tags: ['Efficiency and Optimization', 'Applications', 'Model Architecture', 'WMT', 'Has Code', 'Distillation']
---
Reasoning-enabled large language models (LLMs) excel in logical tasks, yet their utility for evaluating natural language generation remains unexplored. This study systematically compares reasoning LLMs with non-reasoning counterparts across machine translation and text summarization evaluation tasks. We evaluate eight models spanning state-of-the-art reasoning models (DeepSeek-R1, OpenAI o3), their distilled variants (8B-70B parameters), and equivalent non-reasoning LLMs. Experiments on WMT23 and SummEval benchmarks reveal architecture and task-dependent benefits: OpenAI o3-mini models show improved performance with increased reasoning on MT, while DeepSeek-R1 and generally underperforms compared to its non-reasoning variant except in summarization consistency evaluation. Correlation analysis demonstrates that reasoning token usage correlates with evaluation quality only in specific models, while almost all models generally allocate more reasoning tokens when identifying more quality issues. Distillation maintains reasonable performance up to 32B parameter models but degrades substantially at 8B scale. This work provides the first assessment of reasoning LLMs for NLG evaluation and comparison to non-reasoning models. We share our code to facilitate further research: https://github.com/NL2G/reasoning-eval.

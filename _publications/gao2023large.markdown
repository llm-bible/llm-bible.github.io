---
layout: publication
title: Strategyllm Large Language Models As Strategy Generators Executors Optimizers And Evaluators For Problem Solving
authors: Gao Chang, Jiang Haiyun, Cai Deng, Shi Shuming, Lam Wai
conference: "Arxiv"
year: 2023
bibkey: gao2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08803"}
tags: ['Agentic', 'Ethics And Bias', 'Few Shot', 'Prompting', 'Tools']
---
Most existing prompting methods suffer from the issues of generalizability and consistency as they often rely on instance-specific solutions that may not be applicable to other instances and lack task-level consistency across the selected few-shot examples. To address these limitations we propose a comprehensive framework StrategyLLM allowing LLMs to perform inductive reasoning deriving general strategies from specific task instances and deductive reasoning applying these general strategies to particular task examples for constructing generalizable and consistent few-shot prompts. It employs four LLM-based agents strategy generator executor optimizer and evaluator working together to generate evaluate and select promising strategies for a given task. Experimental results demonstrate that StrategyLLM outperforms the competitive baseline CoT-SC that requires human-annotated solutions on 13 datasets across 4 challenging tasks without human involvement including math reasoning (34.237; (rightarrow) 38.837;) commonsense reasoning (70.337; (rightarrow) 72.537;) algorithmic reasoning (73.737; (rightarrow) 85.037;) and symbolic reasoning (30.037; (rightarrow) 79.237;). Further analysis reveals that StrategyLLM is applicable to various LLMs and demonstrates advantages across numerous scenarios.

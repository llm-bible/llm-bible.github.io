---
layout: publication
title: 'SOSBENCH: Benchmarking Safety Alignment On Scientific Knowledge'
authors: Fengqing Jiang, Fengbo Ma, Zhangchen Xu, Yuetai Li, Bhaskar Ramasubramanian, Luyao Niu, Bo Li, Xianyan Chen, Zhen Xiang, Radha Poovendran
conference: "Arxiv"
year: 2025
bibkey: jiang2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21605"}
tags: ['Responsible AI', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting', 'Applications']
---
Large language models (LLMs) exhibit advancing capabilities in complex tasks, such as reasoning and graduate-level question answering, yet their resilience against misuse, particularly involving scientifically sophisticated risks, remains underexplored. Existing safety benchmarks typically focus either on instructions requiring minimal knowledge comprehension (e.g., ``tell me how to build a bomb") or utilize prompts that are relatively low-risk (e.g., multiple-choice or classification tasks about hazardous content). Consequently, they fail to adequately assess model safety when handling knowledge-intensive, hazardous scenarios.
  To address this critical gap, we introduce SOSBench, a regulation-grounded, hazard-focused benchmark encompassing six high-risk scientific domains: chemistry, biology, medicine, pharmacology, physics, and psychology. The benchmark comprises 3,000 prompts derived from real-world regulations and laws, systematically expanded via an LLM-assisted evolutionary pipeline that introduces diverse, realistic misuse scenarios (e.g., detailed explosive synthesis instructions involving advanced chemical formulas). We evaluate frontier models within a unified evaluation framework using our SOSBench. Despite their alignment claims, advanced models consistently disclose policy-violating content across all domains, demonstrating alarmingly high rates of harmful responses (e.g., 79.1% for Deepseek-R1 and 47.3% for GPT-4.1). These results highlight significant safety alignment deficiencies and underscore urgent concerns regarding the responsible deployment of powerful LLMs.

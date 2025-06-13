---
layout: publication
title: 'Generative Evaluation Of Complex Reasoning In Large Language Models'
authors: Haowei Lin, Xiangyu Wang, Ruilin Yan, Baizhou Huang, Haotian Ye, Jianhua Zhu, Zihao Wang, James Zou, Jianzhu Ma, Yitao Liang
conference: "Arxiv"
year: 2025
bibkey: lin2025generative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02810'}
tags: ['Reinforcement Learning', 'Tools', 'Training Techniques']
---
With powerful large language models (LLMs) demonstrating superhuman reasoning
capabilities, a critical question arises: Do LLMs genuinely reason, or do they
merely recall answers from their extensive, web-scraped training datasets?
Publicly released benchmarks inevitably become contaminated once incorporated
into subsequent LLM training sets, undermining their reliability as faithful
assessments. To address this, we introduce KUMO, a generative evaluation
framework designed specifically for assessing reasoning in LLMs. KUMO
synergistically combines LLMs with symbolic engines to dynamically produce
diverse, multi-turn reasoning tasks that are partially observable and
adjustable in difficulty. Through an automated pipeline, KUMO continuously
generates novel tasks across open-ended domains, compelling models to
demonstrate genuine generalization rather than memorization. We evaluated 23
state-of-the-art LLMs on 5,000 tasks across 100 domains created by KUMO,
benchmarking their reasoning abilities against university students. Our
findings reveal that many LLMs have outperformed university-level performance
on easy reasoning tasks, and reasoning-scaled LLMs reach university-level
performance on complex reasoning challenges. Moreover, LLM performance on KUMO
tasks correlates strongly with results on newly released real-world reasoning
benchmarks, underscoring KUMO's value as a robust, enduring assessment tool for
genuine LLM reasoning capabilities.

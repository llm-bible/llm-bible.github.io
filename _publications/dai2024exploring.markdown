---
layout: publication
title: 'MHPP: Exploring The Capabilities And Limitations Of Language Models Beyond Basic Code Generation'
authors: Jianbo Dai, Jianqiao Lu, Yunlong Feng, Dong Huang, Guangtao Zeng, Rongju Ruan, Ming Cheng, Haochen Tan, Zhijiang Guo
conference: "Arxiv"
year: 2024
bibkey: dai2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11430"}
  - {name: "Code", url: "https://github.com/SparksofAGI/MHPP"}
tags: ['Has Code', 'Model Architecture', 'Applications', 'GPT']
---
Recent advancements in large language models (LLMs) have greatly improved
code generation, specifically at the function level. For instance, GPT-4o has
achieved a 91.0% pass rate on HumanEval. However, this draws into question the
adequacy of existing benchmarks in thoroughly assessing function-level code
generation capabilities. Our study analyzed two common benchmarks, HumanEval
and MBPP, and found that these might not thoroughly evaluate LLMs' code
generation capacities due to limitations in quality, difficulty, and
granularity. To resolve this, we introduce the Mostly Hard Python Problems
(MHPP) dataset, consisting of 210 unique human-curated problems. By focusing on
the combination of natural language and code reasoning, MHPP gauges LLMs'
abilities to comprehend specifications and restrictions, engage in multi-step
reasoning, and apply coding knowledge effectively. Initial evaluations of 26
LLMs using MHPP showed many high-performing models on HumanEval failed to
achieve similar success on MHPP. Moreover, MHPP highlighted various previously
undiscovered limitations within various LLMs, leading us to believe that it
could pave the way for a better understanding of LLMs' capabilities and
limitations. MHPP, evaluation pipeline, and leaderboard can be found in
https://github.com/SparksofAGI/MHPP.

---
layout: publication
title: 'Local Prompt Optimization'
authors: Yash Jain, Vishal Chowdhary
conference: "Arxiv"
year: 2025
bibkey: jain2025local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20355"}
tags: ['Prompting', 'Efficiency and Optimization']
---
In recent years, the use of prompts to guide the output of Large Language
Models have increased dramatically. However, even the best of experts struggle
to choose the correct words to stitch up a prompt for the desired task. To
solve this, LLM driven prompt optimization emerged as an important problem.
Existing prompt optimization methods optimize a prompt globally, where in all
the prompt tokens have to be optimized over a large vocabulary while solving a
complex task. The large optimization space (tokens) leads to insufficient
guidance for a better prompt. In this work, we introduce Local Prompt
Optimization (LPO) that integrates with any general automatic prompt
engineering method. We identify the optimization tokens in a prompt and nudge
the LLM to focus only on those tokens in its optimization step. We observe
remarkable performance improvements on Math Reasoning (GSM8k and MultiArith)
and BIG-bench Hard benchmarks across various automatic prompt engineering
methods. Further, we show that LPO converges to the optimal prompt faster than
global methods.

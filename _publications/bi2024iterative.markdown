---
layout: publication
title: 'Iterative Refinement Of Project-level Code Context For Precise Code Generation With Compiler Feedback'
authors: Zhangqian Bi, Yao Wan, Zheng Wang, Hongyu Zhang, Batu Guan, Fangxin Lu, Zili Zhang, Yulei Sui, Hai Jin, Xuanhua Shi
conference: "Arxiv"
year: 2024
bibkey: bi2024iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16792"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Prompting']
---
Large Language Models (LLMs) have shown remarkable progress in automated code
generation. Yet, LLM-generated code may contain errors in API usage, class,
data structure, or missing project-specific information. As much of this
project-specific context cannot fit into the prompts of LLMs, we must find ways
to allow the model to explore the project-level code context. We present
CoCoGen, a new code generation approach that uses compiler feedback to improve
the LLM-generated code. CoCoGen first leverages static analysis to identify
mismatches between the generated code and the project's context. It then
iteratively aligns and fixes the identified errors using information extracted
from the code repository. We integrate CoCoGen with two representative LLMs,
i.e., GPT-3.5-Turbo and Code Llama (13B), and apply it to Python code
generation. Experimental results show that CoCoGen significantly improves the
vanilla LLMs by over 80% in generating code dependent on the project context
and consistently outperforms the existing retrieval-based code generation
baselines.

---
layout: publication
title: Iterative Refinement Of Project45;level Code Context For Precise Code Generation With Compiler Feedback
authors: Bi Zhangqian, Wan Yao, Wang Zheng, Zhang Hongyu, Guan Batu, Lu Fangxin, Zhang Zili, Sui Yulei, Jin Hai, Shi Xuanhua
conference: "Arxiv"
year: 2024
bibkey: bi2024iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16792"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Large Language Models (LLMs) have shown remarkable progress in automated code generation. Yet LLM45;generated code may contain errors in API usage class data structure or missing project45;specific information. As much of this project45;specific context cannot fit into the prompts of LLMs we must find ways to allow the model to explore the project45;level code context. We present CoCoGen a new code generation approach that uses compiler feedback to improve the LLM45;generated code. CoCoGen first leverages static analysis to identify mismatches between the generated code and the projects context. It then iteratively aligns and fixes the identified errors using information extracted from the code repository. We integrate CoCoGen with two representative LLMs i.e. GPT45;3.545;Turbo and Code Llama (13B) and apply it to Python code generation. Experimental results show that CoCoGen significantly improves the vanilla LLMs by over 8037; in generating code dependent on the project context and consistently outperforms the existing retrieval45;based code generation baselines.

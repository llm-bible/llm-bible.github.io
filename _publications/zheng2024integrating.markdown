---
layout: publication
title: Opencodeinterpreter\: Integrating Code Generation With Execution And Refinement
authors: Zheng Tianyu, Zhang Ge, Shen Tianhao, Liu Xueling, Lin Bill Yuchen, Fu Jie, Chen Wenhu, Yue Xiang
conference: "Arxiv"
year: 2024
bibkey: zheng2024integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14658"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
The introduction of large language models has significantly advanced code generation. However open-source models often lack the execution capabilities and iterative refinement of advanced systems like the GPT-4 Code Interpreter. To address this we introduce OpenCodeInterpreter a family of open-source code systems designed for generating executing and iteratively refining code. Supported by Code-Feedback a dataset featuring 68K multi-turn interactions OpenCodeInterpreter integrates execution and human feedback for dynamic code refinement. Our comprehensive evaluation of OpenCodeInterpreter across key benchmarks such as HumanEval MBPP and their enhanced versions from EvalPlus reveals its exceptional performance. Notably OpenCodeInterpreter-33B achieves an accuracy of 83.2 (76.4) on the average (and plus versions) of HumanEval and MBPP closely rivaling GPT-4s 84.2 (76.2) and further elevates to 91.6 (84.6) with synthesized human feedback from GPT-4. OpenCodeInterpreter brings the gap between open-source code generation models and proprietary systems like GPT-4 Code Interpreter.

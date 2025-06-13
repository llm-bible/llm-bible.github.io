---
layout: publication
title: 'Can Large Language Models Understand Intermediate Representations In Compilers?'
authors: Hailong Jiang, Jianfeng Zhu, Yao Wan, Bo Fang, Hongyu Zhang, Ruoming Jin, Qiang Guan
conference: "Arxiv"
year: 2025
bibkey: jiang2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06854"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Intermediate Representations (IRs) play a critical role in compiler design and program analysis, yet their comprehension by Large Language Models (LLMs) remains underexplored. In this paper, we present an explorative empirical study evaluating the capabilities of six state-of-the-art LLMs: GPT-4, GPT-3, DeepSeek, Gemma 2, Llama 3, and Code Llama, in understanding IRs. Specifically, we assess model performance across four core tasks: control flow graph reconstruction, decompilation, code summarization, and execution reasoning. While LLMs exhibit competence in parsing IR syntax and identifying high-level structures, they consistently struggle with instruction-level reasoning, especially in control flow reasoning, loop handling, and dynamic execution. Common failure modes include misinterpreting branching instructions, omitting critical operations, and relying on heuristic reasoning rather than precise instruction-level logic. Our findings highlight the need for IR-specific enhancements in LLM design. We recommend fine-tuning on structured IR datasets and integrating control-flow-sensitive architectures to improve model effectiveness. All experimental data and source code are publicly available at

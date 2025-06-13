---
layout: publication
title: 'Towards Llm-based Optimization Compilers. Can Llms Learn How To Apply A Single Peephole Optimization? Reasoning Is All Llms Need!'
authors: Xiangxin Fang, Lev Mukhanov
conference: "Arxiv"
year: 2024
bibkey: fang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12163"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Applications', 'GPT']
---
Large Language Models (LLMs) have demonstrated great potential in various
language processing tasks, and recent studies have explored their application
in compiler optimizations. However, all these studies focus on the conventional
open-source LLMs, such as Llama2, which lack enhanced reasoning mechanisms. In
this study, we investigate the errors produced by the fine-tuned 7B-parameter
Llama2 model as it attempts to learn and apply a simple peephole optimization
for the AArch64 assembly code. We provide an analysis of the errors produced by
the LLM and compare it with state-of-the-art OpenAI models which implement
advanced reasoning logic, including GPT-4o and GPT-o1 (preview). We demonstrate
that OpenAI GPT-o1, despite not being fine-tuned, outperforms the fine-tuned
Llama2 and GPT-4o. Our findings indicate that this advantage is largely due to
the chain-of-thought reasoning implemented in GPT-o1. We hope our work will
inspire further research on using LLMs with enhanced reasoning mechanisms and
chain-of-thought for code generation and optimization.

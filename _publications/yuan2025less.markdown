---
layout: publication
title: 'LLMSR@XLLM25: Less Is More: Enhancing Structured Multi-agent Reasoning Via Quality-guided Distillation'
authors: Jiahao Yuan, Xingzhe Sun, Xing Yu, Jingwen Wang, Dehui Du, Zhiqing Cui, Zixiang Di
conference: "Arxiv"
year: 2025
bibkey: yuan2025less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16408"}
  - {name: "Code", url: "https://github.com/JhCircle/Less-is-More"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Efficiency and Optimization', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Has Code', 'Few-Shot', 'Prompting', 'Distillation']
---
The LLMSR@XLLM25 formulates a low-resource structural reasoning task that challenges LLMs to generate interpretable, step-by-step rationales with minimal labeled data. We present Less is More, the third-place winning approach in the LLMSR@XLLM25, which focuses on structured reasoning from only 24 labeled examples. Our approach leverages a multi-agent framework with reverse-prompt induction, retrieval-augmented reasoning synthesis via GPT-4o, and dual-stage reward-guided filtering to distill high-quality supervision across three subtasks: question parsing, CoT parsing, and step-level verification. All modules are fine-tuned from Meta-Llama-3-8B-Instruct under a unified LoRA+ setup. By combining structure validation with reward filtering across few-shot and zero-shot prompts, our pipeline consistently improves structure reasoning quality. These results underscore the value of controllable data distillation in enhancing structured inference under low-resource constraints. Our code is available at https://github.com/JhCircle/Less-is-More.

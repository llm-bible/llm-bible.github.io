---
layout: publication
title: 'System-2 Mathematical Reasoning Via Enriched Instruction Tuning'
authors: Huanqia Cai, Yijun Yang, Zhifeng Li
conference: "Arxiv"
year: 2024
bibkey: cai2024system
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16964"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Solving complex mathematical problems via system-2 reasoning is a natural
human skill, yet it remains a significant challenge for current large language
models (LLMs). We identify the scarcity of deliberate multi-step reasoning data
as a primary limiting factor. To this end, we introduce Enriched Instruction
Tuning (EIT), a method that enriches existing human-annotated mathematical
datasets by synergizing human and AI feedback to create fine-grained reasoning
trajectories. These datasets are then used to fine-tune open-source LLMs,
enhancing their mathematical reasoning abilities without reliance on any
symbolic verification program. Concretely, EIT is composed of two critical
steps: Enriching with Reasoning Plan (ERP) and Enriching with Reasoning Step
(ERS). The former generates a high-level plan that breaks down complex
instructions into a sequence of simpler objectives, while ERS fills in
reasoning contexts often overlooked by human annotators, creating a smoother
reasoning trajectory for LLM fine-tuning. Unlike existing CoT prompting methods
that generate reasoning chains only depending on LLM's internal knowledge, our
method leverages human-annotated initial answers as ``meta-knowledge'' to help
LLMs generate more detailed and precise reasoning processes, leading to a more
trustworthy LLM expert for complex mathematical problems. In experiments, EIT
achieves an accuracy of 84.1% on GSM8K and 32.5% on MATH, surpassing
state-of-the-art fine-tuning and prompting methods, and even matching the
performance of tool-augmented methods.

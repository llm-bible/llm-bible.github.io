---
layout: publication
title: 'A Cognitive Writing Perspective For Constrained Long-form Text Generation'
authors: Kaiyang Wan, Honglin Mu, Rui Hao, Haoran Luo, Tianle Gu, Xiuying Chen
conference: "Arxiv"
year: 2025
bibkey: wan2025cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12568"}
  - {name: "Code", url: "https://github.com/KaiyangWan/CogWriter}{CogWriter"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Language Modeling', 'GPT', 'Has Code', 'Applications']
---
Like humans, Large Language Models (LLMs) struggle to generate high-quality long-form text that adheres to strict requirements in a single pass. This challenge is unsurprising, as successful human writing, according to the Cognitive Writing Theory, is a complex cognitive process involving iterative planning, translating, reviewing, and monitoring. Motivated by these cognitive principles, we aim to equip LLMs with human-like cognitive writing capabilities through CogWriter, a novel training-free framework that transforms LLM constrained long-form text generation into a systematic cognitive writing paradigm. Our framework consists of two key modules: (1) a Planning Agent that performs hierarchical planning to decompose the task, and (2) multiple Generation Agents that execute these plans in parallel. The system maintains quality via continuous monitoring and reviewing mechanisms, which evaluate outputs against specified requirements and trigger necessary revisions. CogWriter demonstrates exceptional performance on LongGenBench, a benchmark for complex constrained long-form text generation. Even when using Qwen-2.5-14B as its backbone, CogWriter surpasses GPT-4o by 22% in complex instruction completion accuracy while reliably generating texts exceeding 10,000 words. We hope this cognitive science-inspired approach provides a paradigm for LLM writing advancements: \href\{https://github.com/KaiyangWan/CogWriter\}\{CogWriter\}.

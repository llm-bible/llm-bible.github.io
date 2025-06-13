---
layout: publication
title: 'Beyond Path Selection: Better Llms For Scientific Information Extraction With Mimicsft And Relevance And Rule-induced(r\(^2\))grpo'
authors: Ran Li, Shimin Di, Yuchen Liu, Chen Jing, Yu Qiu, Lei Chen
conference: "Arxiv"
year: 2025
bibkey: li2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22068"}
  - {name: "Code", url: "https://github.com/ranlislz/R2GRPO"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Distillation', 'BERT', 'Fine-Tuning', 'Has Code']
---
Previous study suggest that powerful Large Language Models (LLMs) trained with Reinforcement Learning with Verifiable Rewards (RLVR) only refines reasoning path without improving the reasoning capacity in math tasks while supervised-finetuning(SFT) with distillation can. We study this from the view of Scientific information extraction (SciIE) where LLMs and reasoning LLMs underperforms small Bert-based models. SciIE require both the reasoning and memorization. We argue that both SFT and RLVR can refine the reasoning path and improve reasoning capacity in a simple way based on SciIE. We propose two-stage training with 1. MimicSFT, using structured reasoning templates without needing high-quality chain-of-thought data, 2. R\\(^2\\)GRPO with relevance and rule-induced rewards. Experiments on scientific IE benchmarks show that both methods can improve the reasoning capacity. R\\(^2\\)GRPO with mimicSFT surpasses baseline LLMs and specialized supervised models in relation extraction. Our code is available at https://github.com/ranlislz/R2GRPO.

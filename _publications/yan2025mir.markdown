---
layout: publication
title: 'Mir-bench: Can Your LLM Recognize Complicated Patterns Via Many-shot In-context Reasoning?'
authors: Kai Yan, Zhan Ling, Kang Liu, Yifan Yang, Ting-han Fan, Lingfeng Shen, Zhengyin Du, Jiecao Chen
conference: "Arxiv"
year: 2025
bibkey: yan2025mir
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09933"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
The ability to recognize patterns from examples and apply them to new ones is a primal ability for general intelligence, and is widely studied by psychology and AI researchers. Many benchmarks have been proposed to measure such ability for Large Language Models (LLMs); however, they focus on few-shot (usually <10) setting and lack evaluation for aggregating many pieces of information from long contexts. On the other hand, the ever-growing context length of LLMs have brought forth the novel paradigm of many-shot In-Context Learning (ICL), which addresses new tasks with hundreds to thousands of examples without expensive and inefficient fine-tuning. However, many-shot evaluations often focus on classification, and popular long-context LLM tasks such as Needle-In-A-Haystack (NIAH) seldom require complicated intelligence for integrating many pieces of information. To fix the issues from both worlds, we propose MIR-Bench, the first many-shot in-context reasoning benchmark for pattern recognition that asks LLM to predict output via input-output examples from underlying functions with diverse data format. Based on MIR-Bench, we study many novel problems for many-shot in-context reasoning, and acquired many insightful findings including scaling effect, robustness, inductive vs. transductive reasoning, retrieval Augmented Generation (RAG), coding for inductive reasoning, cross-domain generalizability, etc.

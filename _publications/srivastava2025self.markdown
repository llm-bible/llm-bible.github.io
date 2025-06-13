---
layout: publication
title: 'DEBATE, TRAIN, EVOLVE: Self Evolution Of Language Model Reasoning'
authors: Gaurav Srivastava, Zhenyu Bi, Meng Lu, Xuan Wang
conference: "Arxiv"
year: 2025
bibkey: srivastava2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15734"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'RAG', 'Prompting']
---
Large language models (LLMs) have improved significantly in their reasoning through extensive training on massive datasets. However, relying solely on additional data for improvement is becoming increasingly impractical, highlighting the need for models to autonomously enhance their reasoning without external supervision. In this paper, we propose Debate, Train, Evolve (DTE), a novel ground truth-free training framework that uses multi-agent debate traces to evolve a single language model. We also introduce a new prompting strategy Reflect-Critique-Refine, to improve debate quality by explicitly instructing agents to critique and refine their reasoning. Extensive evaluations on five reasoning benchmarks with six open-weight models show that our DTE framework achieve substantial improvements, with an average accuracy gain of 8.92% on the challenging GSM-PLUS dataset. Furthermore, we observe strong cross-domain generalization, with an average accuracy gain of 5.8% on all other benchmarks, suggesting that our method captures general reasoning capabilities.

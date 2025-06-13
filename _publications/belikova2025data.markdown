---
layout: publication
title: 'Data-efficient Meta-models For Evaluation Of Context-based Questions And Answers In Llms'
authors: Julia Belikova, Konstantin Polev, Rauf Parchiev, Dmitry Simakov
conference: "Arxiv"
year: 2025
bibkey: belikova2025data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23299'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) systems are increasingly deployed in industry applications, yet their reliability remains hampered by challenges in detecting hallucinations. While supervised state-of-the-art (SOTA) methods that leverage LLM hidden states -- such as activation tracing and representation analysis -- show promise, their dependence on extensively annotated datasets limits scalability in real-world applications. This paper addresses the critical bottleneck of data annotation by investigating the feasibility of reducing training data requirements for two SOTA hallucination detection frameworks: Lookback Lens, which analyzes attention head dynamics, and probing-based approaches, which decode internal model representations. We propose a methodology combining efficient classification algorithms with dimensionality reduction techniques to minimize sample size demands while maintaining competitive performance. Evaluations on standardized question-answering RAG benchmarks show that our approach achieves performance comparable to strong proprietary LLM-based baselines with only 250 training samples. These results highlight the potential of lightweight, data-efficient paradigms for industrial deployment, particularly in annotation-constrained scenarios.

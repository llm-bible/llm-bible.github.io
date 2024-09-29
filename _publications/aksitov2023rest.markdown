---
layout: publication
title: Rest Meets React: Self-improvement For Multi-step Reasoning LLM Agent
authors: Aksitov Renat, Miryoosefi Sobhan, Li Zonglin, Li Daliang, Babayan Sheila, Kopparapu Kavya, Fisher Zachary, Guo Ruiqi, Prakash Sushant, Srinivasan Pranesh, Zaheer Manzil, Yu Felix, Kumar Sanjiv
conference: "Arxiv"
year: 2023
bibkey: aksitov2023rest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10003"}
tags: ['Agentic', 'Distillation', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Answering complex natural language questions often necessitates multi-step reasoning and integrating external information. Several systems have combined knowledge retrieval with a large language model (LLM) to answer such questions. These systems however suffer from various failure cases and we cannot directly train them end-to-end to fix such failures as interaction with external knowledge is non-differentiable. To address these deficiencies we define a ReAct-style LLM agent with the ability to reason and act upon external knowledge. We further refine the agent through a ReST-like method that iteratively trains on previous trajectories employing growing-batch reinforcement learning with AI feedback for continuous self-improvement and self-distillation. Starting from a prompted large model and after just two iterations of the algorithm we can produce a fine-tuned small model that achieves comparable performance on challenging compositional question-answering benchmarks with two orders of magnitude fewer parameters.

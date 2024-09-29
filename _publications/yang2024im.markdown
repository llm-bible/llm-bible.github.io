---
layout: publication
title: IM-RAG Multi-round Retrieval-augmented Generation Through Learning Inner Monologues
authors: Yang Diji, Rao Jinmeng, Chen Kezhen, Guo Xiaoyuan, Zhang Yawen, Yang Jie, Zhang Yi
conference: "Arxiv"
year: 2024
bibkey: yang2024im
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13021"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Interpretability And Explainability', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Although the Retrieval-Augmented Generation (RAG) paradigms can use external knowledge to enhance and ground the outputs of Large Language Models (LLMs) to mitigate generative hallucinations and static knowledge base problems they still suffer from limited flexibility in adopting Information Retrieval (IR) systems with varying capabilities constrained interpretability during the multi-round retrieval process and a lack of end-to-end optimization. To address these challenges we propose a novel LLM-centric approach IM-RAG that integrates IR systems with LLMs to support multi-round RAG through learning Inner Monologues (IM i.e. the human inner voice that narrates ones thoughts). During the IM process the LLM serves as the core reasoning model (i.e. Reasoner) to either propose queries to collect more information via the Retriever or to provide a final answer based on the conversational context. We also introduce a Refiner that improves the outputs from the Retriever effectively bridging the gap between the Reasoner and IR modules with varying capabilities and fostering multi-round communications. The entire IM process is optimized via Reinforcement Learning (RL) where a Progress Tracker is incorporated to provide mid-step rewards and the answer prediction is further separately optimized via Supervised Fine-Tuning (SFT). We conduct extensive experiments with the HotPotQA dataset a popular benchmark for retrieval-based multi-step question-answering. The results show that our approach achieves state-of-the-art (SOTA) performance while providing high flexibility in integrating IR modules as well as strong interpretability exhibited in the learned inner monologues.

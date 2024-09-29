---
layout: publication
title: Llms Instruct Llmsan Extraction And Editing Method
authors: Zhang Xin, Ju Tianjie, Liang Huijia, Fu Ying, Zhang Qin
conference: "Arxiv"
year: 2024
bibkey: zhang2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15736"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The interest in updating Large Language Models (LLMs) without retraining from scratch is substantial yet it comes with some challenges.This is especially true for situations demanding complex reasoning with limited samples a scenario we refer to as the Paucity-Constrained Complex Reasoning Adaptation for LLMs (PCRA-LLM).Traditional methods like Low-Rank Adaptation (LoRA) and Retrieval-Augmented Generation (RAG) are inadequate for this critical issue particularly evident in our exploration of a specific medical context that epitomize the PCRA-LLMs distinct needs.To address the issue we propose a Sequential Fusion method to incorporate knowledge from complex context into LLMs. This method employs a two-stage framework initially it leverages general LLMs to construct knowledge graphs (KGs) for extracting knowledge from complex texts; subsequently it updates the domain LLMs through knowledge edit. According to our method the domain LLM achieved a 71.6937; accuracy in question answering tasks. Subsequently we broadened our assessment to a novel dataset we developed in the economics and management field where our method realized a 7537; accuracy. These outcomes underline the efficacy and adaptability of our approach for PCRA-LLM across various domains.

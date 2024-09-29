---
layout: publication
title: A Large Language Model Enhanced Conversational Recommender System
authors: Feng Yue, Liu Shuchang, Xue Zhenghai, Cai Qingpeng, Hu Lantao, Jiang Peng, Gai Kun, Sun Fei
conference: "Arxiv"
year: 2023
bibkey: feng2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06212"}
tags: ['Agentic', 'Interpretability And Explainability', 'RAG', 'Reinforcement Learning']
---
Conversational recommender systems (CRSs) aim to recommend high-quality items to users through a dialogue interface. It usually contains multiple sub-tasks such as user preference elicitation recommendation explanation and item information search. To develop effective CRSs there are some challenges 1) how to properly manage sub-tasks; 2) how to effectively solve different sub-tasks; and 3) how to correctly generate responses that interact with users. Recently Large Language Models (LLMs) have exhibited an unprecedented ability to reason and generate presenting a new opportunity to develop more powerful CRSs. In this work we propose a new LLM-based CRS referred to as LLMCRS to address the above challenges. For sub-task management we leverage the reasoning ability of LLM to effectively manage sub-task. For sub-task solving we collaborate LLM with expert models of different sub-tasks to achieve the enhanced performance. For response generation we utilize the generation ability of LLM as a language interface to better interact with users. Specifically LLMCRS divides the workflow into four stages sub-task detection model matching sub-task execution and response generation. LLMCRS also designs schema-based instruction demonstration-based instruction dynamic sub-task and model matching and summary-based generation to instruct LLM to generate desired results in the workflow. Finally to adapt LLM to conversational recommendations we also propose to fine-tune LLM with reinforcement learning from CRSs performance feedback referred to as RLPF. Experimental results on benchmark datasets show that LLMCRS with RLPF outperforms the existing methods.

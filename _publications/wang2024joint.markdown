---
layout: publication
title: JMLR Joint Medical LLM And Retrieval Training For Enhancing Reasoning And Professional Question Answering Capability
authors: Wang Junda, Yang Zhichao, Yao Zonghai, Yu Hong
conference: "Arxiv"
year: 2024
bibkey: wang2024joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17887"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated a remarkable potential in medical knowledge acquisition and question45;answering. However LLMs can potentially hallucinate and yield factually incorrect outcomes even with domain45;specific pretraining. Previously retrieval augmented generation (RAG) has limited success in addressing hallucinations. Unlike previous methods in RAG where the retrieval model was trained separately from the LLM we introduce JMLR (for Jointly trains LLM and information Retrieval) during the fine45;tuning phase. The synchronized training mechanism enhances JMLRs ability to retrieve clinical guidelines and leverage medical knowledge to reason and answer questions and reduces the demand for computational resources. We evaluated JMLR on the important medical question45;answering application. Our experimental results demonstrate that JMLR45;13B (70.537;) outperforms a previous state45;of45;the45;art open45;source model using conventional pre45;training and fine45;tuning Meditron45;70B (68.937;) and Llama245;13B with RAG (67.737;) on a medical question45;answering dataset. Comprehensive evaluations reveal JMLR45;13B enhances reasoning quality and reduces hallucinations better than Claude345;Opus. Additionally JMLR45;13B (148 GPU hours) also trains much faster than Meditron45;70B (42630 GPU hours). Through this work we provide a new and efficient knowledge enhancement method for healthcare demonstrating the potential of integrating retrieval and LLM training for medical question45;answering systems.

---
layout: publication
title: JMLR Joint Medical LLM and Retrieval Training for Enhancing Reasoning and Professional Question Answering Capability
authors: Wang Junda, Yang Zhichao, Yao Zonghai, Yu Hong
conference: "Arxiv"
year: 2024
bibkey: wang2024jmlr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17887"}
tags: ['ARXIV', 'Applications', 'Fine Tuning', 'LLM', 'RAG', 'Tools']
---
Large Language Models (LLMs) have demonstrated a remarkable potential in medical knowledge acquisition and question-answering. However LLMs can potentially hallucinate and yield factually incorrect outcomes even with domain-specific pretraining. Previously retrieval augmented generation (RAG) has limited success in addressing hallucinations. Unlike previous methods in RAG where the retrieval model was trained separately from the LLM we introduce JMLR (for Jointly trains LLM and information Retrieval) during the fine-tuning phase. The synchronized training mechanism enhances JMLRs ability to retrieve clinical guidelines and leverage medical knowledge to reason and answer questions and reduces the demand for computational resources. We evaluated JMLR on the important medical question-answering application. Our experimental results demonstrate that JMLR-13B (70.5) outperforms a previous state-of-the-art open-source model using conventional pre-training and fine-tuning Meditron-70B (68.9) and Llama2-13B with RAG (67.7) on a medical question-answering dataset. Comprehensive evaluations reveal JMLR-13B enhances reasoning quality and reduces hallucinations better than Claude3-Opus. Additionally JMLR-13B (148 GPU hours) also trains much faster than Meditron-70B (42630 GPU hours). Through this work we provide a new and efficient knowledge enhancement method for healthcare demonstrating the potential of integrating retrieval and LLM training for medical question-answering systems.

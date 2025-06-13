---
layout: publication
title: 'Beyond Chains: Bridging Large Language Models And Knowledge Bases In Complex Question Answering'
authors: Yihua Zhu, Qianying Liu, Akiko Aizawa, Hidetoshi Shimodaira
conference: "Arxiv"
year: 2025
bibkey: zhu2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14099'}
tags: ['Agentic', 'RAG', 'Applications', 'Tools', 'Ethics and Bias', 'Interpretability']
---
Knowledge Base Question Answering (KBQA) aims to answer natural language questions using structured knowledge from KBs. While LLM-only approaches offer generalization, they suffer from outdated knowledge, hallucinations, and lack of transparency. Chain-based KG-RAG methods address these issues by incorporating external KBs, but are limited to simple chain-structured questions due to the absence of planning and logical structuring. Inspired by semantic parsing methods, we propose PDRR: a four-stage framework consisting of Predict, Decompose, Retrieve, and Reason. Our method first predicts the question type and decomposes the question into structured triples. Then retrieves relevant information from KBs and guides the LLM as an agent to reason over and complete the decomposed triples. Experimental results demonstrate that PDRR consistently outperforms existing methods across various LLM backbones and achieves superior performance on both chain-structured and non-chain complex questions.

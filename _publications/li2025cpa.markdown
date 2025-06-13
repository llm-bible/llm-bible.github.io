---
layout: publication
title: 'Cpa-rag:covert Poisoning Attacks On Retrieval-augmented Generation In Large Language Models'
authors: Chunyang Li, Junwei Zhang, Anda Cheng, Zhuo Ma, Xinghua Li, Jianfeng Ma
conference: "Arxiv"
year: 2025
bibkey: li2025cpa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19864"}
tags: ['Security', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'Prompting', 'Applications']
---
Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by incorporating external knowledge, but its openness introduces vulnerabilities that can be exploited by poisoning attacks. Existing poisoning methods for RAG systems have limitations, such as poor generalization and lack of fluency in adversarial texts. In this paper, we propose CPA-RAG, a black-box adversarial framework that generates query-relevant texts capable of manipulating the retrieval process to induce target answers. The proposed method integrates prompt-based text generation, cross-guided optimization through multiple LLMs, and retriever-based scoring to construct high-quality adversarial samples. We conduct extensive experiments across multiple datasets and LLMs to evaluate its effectiveness. Results show that the framework achieves over 90% attack success when the top-k retrieval setting is 5, matching white-box performance, and maintains a consistent advantage of approximately 5 percentage points across different top-k values. It also outperforms existing black-box baselines by 14.5 percentage points under various defense strategies. Furthermore, our method successfully compromises a commercial RAG system deployed on Alibaba's BaiLian platform, demonstrating its practical threat in real-world applications. These findings underscore the need for more robust and secure RAG frameworks to defend against poisoning attacks.

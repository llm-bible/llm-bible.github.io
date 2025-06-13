---
layout: publication
title: 'BRIEF: Bridging Retrieval And Inference For Multi-hop Reasoning Via Compression'
authors: Yuankai Li, Jia-chen Gu, Di Wu, Kai-wei Chang, Nanyun Peng
conference: "Arxiv"
year: 2024
bibkey: li2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15277"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Merging', 'GPT', 'Applications']
---
Retrieval-augmented generation (RAG) can supplement large language models
(LLMs) by integrating external knowledge. However, as the number of retrieved
documents increases, the input length to LLMs grows linearly, causing a
dramatic increase in latency and a degradation in long-context understanding.
This is particularly serious for multi-hop questions that require a chain of
reasoning across documents. To accelerate inference, reduce costs, and minimize
distractions, this paper presents BRIEF (Bridging Retrieval and Inference
through Evidence Fusion), a lightweight approach that performs query-aware
multi-hop reasoning by compressing retrieved documents into highly dense
textual summaries to integrate into in-context RAG. To enable learning
compression for multi-hop reasoning, we curate synthetic data by extracting
atomic propositions that encapsulate distinct factoids from the source
documents to compose synthetic summaries. Based on our synthetic data built
entirely by open-source models, BRIEF generates more concise summaries and
enables a range of LLMs to achieve exceptional open-domain question answering
(QA) performance. For example, on HotpotQA, BRIEF improves the compression rate
by 2 times compared to the state-of-the-art baseline, while outperforming it by
3.00% EM and 4.16% F1 with Flan-UL2 as the reader model. It also generates more
concise summaries than proprietary GPT-3.5, while demonstrating nearly
identical QA performance.

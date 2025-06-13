---
layout: publication
title: 'Redeep: Detecting Hallucination In Retrieval-augmented Generation Via Mechanistic Interpretability'
authors: Zhongxiang Sun, Xiaoxue Zang, Kai Zheng, Yang Song, Jun Xu, Xiao Zhang, Weijie Yu, Yang Song, Han Li
conference: "Arxiv"
year: 2024
bibkey: sun2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11414"}
tags: ['RAG', 'Interpretability and Explainability']
---
Retrieval-Augmented Generation (RAG) models are designed to incorporate
external knowledge, reducing hallucinations caused by insufficient parametric
(internal) knowledge. However, even with accurate and relevant retrieved
content, RAG models can still produce hallucinations by generating outputs that
conflict with the retrieved information. Detecting such hallucinations requires
disentangling how Large Language Models (LLMs) utilize external and parametric
knowledge. Current detection methods often focus on one of these mechanisms or
without decoupling their intertwined effects, making accurate detection
difficult. In this paper, we investigate the internal mechanisms behind
hallucinations in RAG scenarios. We discover hallucinations occur when the
Knowledge FFNs in LLMs overemphasize parametric knowledge in the residual
stream, while Copying Heads fail to effectively retain or integrate external
knowledge from retrieved content. Based on these findings, we propose ReDeEP, a
novel method that detects hallucinations by decoupling LLM's utilization of
external context and parametric knowledge. Our experiments show that ReDeEP
significantly improves RAG hallucination detection accuracy. Additionally, we
introduce AARF, which mitigates hallucinations by modulating the contributions
of Knowledge FFNs and Copying Heads.

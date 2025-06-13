---
layout: publication
title: 'BIDER: Bridging Knowledge Inconsistency For Efficient Retrieval-augmented Llms Via Key Supporting Evidence'
authors: Jiajie Jin, Yutao Zhu, Yujia Zhou, Zhicheng Dou
conference: "Arxiv"
year: 2024
bibkey: jin2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12174"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Retrieval-augmented large language models (LLMs) have demonstrated efficacy
in knowledge-intensive tasks such as open-domain QA, addressing inherent
challenges in knowledge update and factual inadequacy. However, inconsistencies
between retrieval knowledge and the necessary knowledge for LLMs, leading to a
decline in LLM's answer quality. This paper introduces BIDER, an approach that
refines retrieval documents into Key Supporting Evidence (KSE) through
knowledge synthesis, supervised fine-tuning (SFT), and preference alignment. We
train BIDER by learning from crafting KSE, while maximizing its output to align
with LLM's information acquisition preferences through reinforcement learning.
Evaluations across five datasets show BIDER boosts LLMs' answer quality by 7%
while reducing input content length in retrieval documents by 80%,
outperforming existing methods. The proposed KSE simulation effectively equips
LLMs with essential information for accurate question answering.

---
layout: publication
title: 'Benchmarking LLM Faithfulness In RAG With Evolving Leaderboards'
authors: Manveer Singh Tamber, Forrest Sheng Bao, Chenyu Xu, Ge Luo, Suleman Kazi, Minseok Bae, Miaoran Li, Ofer Mendelevitch, Renyi Qu, Jimmy Lin
conference: "Arxiv"
year: 2025
bibkey: tamber2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04847'}
tags: ['Reinforcement Learning', 'Few-Shot', 'RAG', 'Applications']
---
Hallucinations remain a persistent challenge for LLMs. RAG aims to reduce
hallucinations by grounding responses in contexts. However, even when provided
context, LLMs still frequently introduce unsupported information or
contradictions. This paper presents our efforts to measure LLM hallucinations
with a focus on summarization tasks, assessing how often various LLMs introduce
hallucinations when summarizing documents. We discuss Vectara's existing LLM
hallucination leaderboard, based on the Hughes Hallucination Evaluation Model
(HHEM). While HHEM and Vectara's Hallucination Leaderboard have garnered great
research interest, we examine challenges faced by HHEM and current
hallucination detection methods by analyzing the effectiveness of these methods
on existing hallucination datasets. To address these limitations, we propose
FaithJudge, an LLM-as-a-judge approach guided by few-shot human hallucination
annotations, which substantially improves automated LLM hallucination
evaluation over current methods. We introduce an enhanced hallucination
leaderboard centered on FaithJudge, alongside our current hallucination
leaderboard, enabling more reliable benchmarking of LLMs for hallucinations in
RAG.

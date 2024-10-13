---
layout: publication
title: 'Speculative RAG: Enhancing Retrieval Augmented Generation Through Drafting'
authors: Wang Zilong, Wang Zifeng, Le Long, Zheng Huaixiu Steven, Mishra Swaroop, Perot Vincent, Zhang Yuwei, Mattapalli Anush, Taly Ankur, Shang Jingbo, Lee Chen-yu, Pfister Tomas
conference: "Arxiv"
year: 2024
bibkey: wang2024speculative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08223"}
tags: ['Ethics And Bias', 'RAG', 'Tools']
---
Retrieval augmented generation (RAG) combines the generative abilities of
large language models (LLMs) with external knowledge sources to provide more
accurate and up-to-date responses. Recent RAG advancements focus on improving
retrieval outcomes through iterative LLM refinement or self-critique
capabilities acquired through additional instruction tuning of LLMs. In this
work, we introduce Speculative RAG - a framework that leverages a larger
generalist LM to efficiently verify multiple RAG drafts produced in parallel by
a smaller, distilled specialist LM. Each draft is generated from a distinct
subset of retrieved documents, offering diverse perspectives on the evidence
while reducing input token counts per draft. This approach enhances
comprehension of each subset and mitigates potential position bias over long
context. Our method accelerates RAG by delegating drafting to the smaller
specialist LM, with the larger generalist LM performing a single verification
pass over the drafts. Extensive experiments demonstrate that Speculative RAG
achieves state-of-the-art performance with reduced latency on TriviaQA,
MuSiQue, PubHealth, and ARC-Challenge benchmarks. It notably enhances accuracy
by up to 12.97% while reducing latency by 51% compared to conventional RAG
systems on PubHealth.

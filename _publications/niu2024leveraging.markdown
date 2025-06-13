---
layout: publication
title: 'Judgerank: Leveraging Large Language Models For Reasoning-intensive Reranking'
authors: Tong Niu, Shafiq Joty, Ye Liu, Caiming Xiong, Yingbo Zhou, Semih Yavuz
conference: "Arxiv"
year: 2024
bibkey: niu2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00142"}
tags: ['RAG', 'Agentic', 'Applications']
---
Accurate document retrieval is crucial for the success of retrieval-augmented
generation (RAG) applications, including open-domain question answering and
code completion. While large language models (LLMs) have been employed as dense
encoders or listwise rerankers in RAG systems, they often struggle with
reasoning-intensive tasks because they lack nuanced analysis when judging
document relevance. To address this limitation, we introduce JudgeRank, a novel
agentic reranker that emulates human cognitive processes when assessing
document relevance. Our approach consists of three key steps: (1) query
analysis to identify the core problem, (2) document analysis to extract a
query-aware summary, and (3) relevance judgment to provide a concise assessment
of document relevance. We evaluate JudgeRank on the reasoning-intensive BRIGHT
benchmark, demonstrating substantial performance improvements over first-stage
retrieval methods and outperforming other popular reranking approaches. In
addition, JudgeRank performs on par with fine-tuned state-of-the-art rerankers
on the popular BEIR benchmark, validating its zero-shot generalization
capability. Through comprehensive ablation studies, we demonstrate that
JudgeRank's performance generalizes well across LLMs of various sizes while
ensembling them yields even more accurate reranking than individual models.

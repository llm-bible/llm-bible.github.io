---
layout: publication
title: 'What''s Wrong? Refining Meeting Summaries With LLM Feedback'
authors: Kirstein Frederic, Ruas Terry, Gipp Bela
conference: "Arxiv"
year: 2024
bibkey: kirstein2024refining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11919"}
tags: ['Applications', 'Language Modeling', 'RAG', 'Security', 'Survey Paper']
---
Meeting summarization has become a critical task since digital encounters have become a common practice. Large language models (LLMs) show great potential in summarization offering enhanced coherence and context understanding compared to traditional methods. However they still struggle to maintain relevance and avoid hallucination. We introduce a multi-LLM correction approach for meeting summarization using a two-phase process that mimics the human review process mistake identification and summary refinement. We release QMSum Mistake a dataset of 200 automatically generated meeting summaries annotated by humans on nine error types including structural omission and irrelevance errors. Our experiments show that these errors can be identified with high accuracy by an LLM. We transform identified mistakes into actionable feedback to improve the quality of a given summary measured by relevance informativeness conciseness and coherence. This post-hoc refinement effectively improves summary quality by leveraging multiple LLMs to validate output quality. Our multi-LLM approach for meeting summarization shows potential for similar complex text generation tasks requiring robustness action planning and discussion towards a goal.

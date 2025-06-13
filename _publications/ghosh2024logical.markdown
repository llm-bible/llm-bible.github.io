---
layout: publication
title: 'Logical Consistency Of Large Language Models In Fact-checking'
authors: Bishwamittra Ghosh, Sarah Hasan, Naheed Anjum Arafat, Arijit Khan
conference: "Arxiv"
year: 2024
bibkey: ghosh2024logical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16100"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
In recent years, large language models (LLMs) have demonstrated significant
success in performing varied natural language tasks such as language
translation, question-answering, summarizing, fact-checking, etc. Despite LLMs'
impressive ability to generate human-like texts, LLMs are infamous for their
inconsistent responses - a meaning-preserving change in the input query results
in an inconsistent response and attributes to vulnerabilities of LLMs such as
hallucination. Consequently, existing research focuses on simple
paraphrasing-based consistency assessment of LLMs, and ignores complex queries
that necessitate an even better understanding of logical reasoning by an LLM.
Our work therefore addresses the logical inconsistency of LLMs under complex
logical queries with primitive logical operators, e.g., negation, conjunction,
and disjunction. As a test bed, we consider retrieval-augmented LLMs on a
fact-checking task involving propositional logic queries from knowledge graphs
(KGs). Our contributions are threefold. Benchmark: We introduce three logical
fact-checking datasets over KGs for community development towards logically
consistent LLMs. Assessment: We propose consistency measures of LLMs on
propositional logic queries and demonstrate that existing LLMs lack logical
consistency, especially on complex queries. Improvement: We employ supervised
fine-tuning to improve the logical consistency of LLMs on the complex
fact-checking task with KG contexts. We have made our source code and
benchmarks available.

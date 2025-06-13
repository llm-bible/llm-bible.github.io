---
layout: publication
title: 'Enhancing Domain-specific Retrieval-augmented Generation: Synthetic Data Generation And Evaluation Using Reasoning Models'
authors: Aryan Jadon, Avinash Patil, Shashank Kumar
conference: "Arxiv"
year: 2025
bibkey: jadon2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15854'}
  - {name: "Code", url: 'https://github.com/aryan-jadon/Synthetic-Data-Generation-and-Evaluation-using-Reasoning-Model'}
tags: ['RAG', 'Has Code', 'Security', 'Tools']
---
Retrieval-Augmented Generation (RAG) systems face significant performance
gaps when applied to technical domains requiring precise information extraction
from complex documents. Current evaluation methodologies relying on
document-level metrics inadequately capture token-resolution retrieval accuracy
that is critical for domain-related documents. We propose a framework combining
granular evaluation metrics with synthetic data generation to optimize
domain-specific RAG performance. First, we introduce token-aware metrics
Precision \\(Ω\\) and Intersection-over-Union (IoU) that quantify context
preservation versus information density trade-offs inherent in technical texts.
Second, we develop a reasoning model-driven pipeline using instruction-tuned
LLMs (DeepSeek-R1, DeepSeek-R1 distilled variants, and Phi-4) to generate
context-anchored QA pairs with discontinuous reference spans across three
specialized corpora: SEC 10-K filings (finance), biomedical abstracts (PubMed),
and APT threat reports (cybersecurity).
  Our empirical analysis reveals critical insights: smaller chunks (less than
10 tokens) improve precision by 31-42% (IoU = 0.071 vs. baseline 0.053) at
recall costs (-18%), while domain-specific embedding strategies yield 22%
variance in optimal chunk sizing (5-20 tokens). The
DeepSeek-R1-Distill-Qwen-32B model demonstrates superior concept alignment
(+14% mean IoU over alternatives), though no configuration universally
dominates. Financial texts favor larger chunks for risk factor coverage (Recall
= 0.81 at size = 20), whereas cybersecurity content benefits from atomic
segmentation, Precision \\(Ω = 0.28\\) at size = 5.
  Our code is available on
https://github.com/aryan-jadon/Synthetic-Data-Generation-and-Evaluation-using-Reasoning-Model

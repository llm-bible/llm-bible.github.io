---
layout: publication
title: 'Semantic Caching Of Contextual Summaries For Efficient Question-answering With Language Models'
authors: Camille Couturier, Spyros Mastorakis, Haiying Shen, Saravan Rajmohan, Victor Rühle
conference: "Arxiv"
year: 2025
bibkey: couturier2025semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11271"}
tags: ['RAG', 'Tools', 'Arxiv']
---
Large Language Models (LLMs) are increasingly deployed across edge and cloud platforms for real-time question-answering and retrieval-augmented generation. However, processing lengthy contexts in distributed systems incurs high computational overhead, memory usage, and network bandwidth. This paper introduces a novel semantic caching approach for storing and reusing intermediate contextual summaries, enabling efficient information reuse across similar queries in LLM-based QA workflows. Our method reduces redundant computations by up to 50-60% while maintaining answer accuracy comparable to full document processing, as demonstrated on NaturalQuestions, TriviaQA, and a synthetic ArXiv dataset. This approach balances computational cost and response quality, critical for real-time AI assistants.

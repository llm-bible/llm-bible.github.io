---
layout: publication
title: 'Neoqa: Evidence-based Question Answering With Generated News Events'
authors: Max Glockner, Xiang Jiang, Leonardo F. R. Ribeiro, Iryna Gurevych, Markus Dreyer
conference: "Arxiv"
year: 2025
bibkey: glockner2025evidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05949"}
tags: ['Tools', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Evaluating Retrieval-Augmented Generation (RAG) in large language models (LLMs) is challenging because benchmarks can quickly become stale. Questions initially requiring retrieval may become answerable from pretraining knowledge as newer models incorporate more recent information during pretraining, making it difficult to distinguish evidence-based reasoning from recall. We introduce NeoQA (News Events for Out-of-training Question Answering), a benchmark designed to address this issue. To construct NeoQA, we generated timelines and knowledge bases of fictional news events and entities along with news articles and Q\&A pairs to prevent LLMs from leveraging pretraining knowledge, ensuring that no prior evidence exists in their training data. We propose our dataset as a new platform for evaluating evidence-based question answering, as it requires LLMs to generate responses exclusively from retrieved evidence and only when sufficient evidence is available. NeoQA enables controlled evaluation across various evidence scenarios, including cases with missing or misleading details. Our findings indicate that LLMs struggle to distinguish subtle mismatches between questions and evidence, and suffer from short-cut reasoning when key information required to answer a question is missing from the evidence, underscoring key limitations in evidence-based reasoning.

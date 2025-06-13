---
layout: publication
title: 'Eliciting Critical Reasoning In Retrieval-augmented Language Models Via Contrastive Explanations'
authors: Leonardo Ranaldi, Marco Valentino, Andrè Freitas
conference: "Arxiv"
year: 2024
bibkey: ranaldi2024eliciting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22874"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Interpretability and Explainability', 'Prompting']
---
Retrieval-augmented generation (RAG) has emerged as a critical mechanism in
contemporary NLP to support Large Language Models(LLMs) in systematically
accessing richer factual context. However, the integration of RAG mechanisms
brings its inherent challenges, as LLMs need to deal with potentially noisy
contexts. Recent studies have shown that LLMs still struggle to critically
analyse RAG-based in-context information, a limitation that may lead to
incorrect inferences and hallucinations. In this paper, we investigate how to
elicit critical reasoning in RAG via contrastive explanations. In particular,
we propose Contrastive-RAG (C-RAG), a framework that (i) retrieves relevant
documents given a query, (ii) selects and exemplifies relevant passages, and
(iii) generates explanations that explicitly contrast the relevance of the
passages to (iv) support the final answer. We show the impact of C-RAG building
contrastive reasoning demonstrations from LLMs to instruct smaller models for
retrieval-augmented tasks. Extensive experiments demonstrate that C-RAG
improves state-of-the-art RAG models while (a) requiring significantly fewer
prompts and demonstrations and (b) being robust to perturbations in the
retrieved documents.

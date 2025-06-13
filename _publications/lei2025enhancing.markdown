---
layout: publication
title: 'Factcg: Enhancing Fact Checkers With Graph-based Multi-hop Data'
authors: Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching, Alex Deng
conference: "Arxiv"
year: 2025
bibkey: lei2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17144"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Prompting']
---
Prior research on training grounded factuality classification models to
detect hallucinations in large language models (LLMs) has relied on public
natural language inference (NLI) data and synthetic data. However, conventional
NLI datasets are not well-suited for document-level reasoning, which is
critical for detecting LLM hallucinations. Recent approaches to document-level
synthetic data generation involve iteratively removing sentences from documents
and annotating factuality using LLM-based prompts. While effective, this method
is computationally expensive for long documents and limited by the LLM's
capabilities. In this work, we analyze the differences between existing
synthetic training data used in state-of-the-art models and real LLM output
claims. Based on our findings, we propose a novel approach for synthetic data
generation, CG2C, that leverages multi-hop reasoning on context graphs
extracted from documents. Our fact checker model, FactCG, demonstrates improved
performance with more connected reasoning, using the same backbone models.
Experiments show it even outperforms GPT-4-o on the LLM-Aggrefact benchmark
with much smaller model size.

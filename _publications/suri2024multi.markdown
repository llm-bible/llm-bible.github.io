---
layout: publication
title: 'Visdom: Multi-document QA With Visually Rich Elements Using Multimodal Retrieval-augmented Generation'
authors: Manan Suri, Puneet Mathur, Franck Dernoncourt, Kanika Goswami, Ryan A. Rossi, Dinesh Manocha
conference: "Arxiv"
year: 2024
bibkey: suri2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10704"}
tags: ['Applications', 'RAG', 'Merging', 'Reinforcement Learning', 'Multimodal Models']
---
Understanding information from a collection of multiple documents,
particularly those with visually rich elements, is important for
document-grounded question answering. This paper introduces VisDoMBench, the
first comprehensive benchmark designed to evaluate QA systems in multi-document
settings with rich multimodal content, including tables, charts, and
presentation slides. We propose VisDoMRAG, a novel multimodal Retrieval
Augmented Generation (RAG) approach that simultaneously utilizes visual and
textual RAG, combining robust visual retrieval capabilities with sophisticated
linguistic reasoning. VisDoMRAG employs a multi-step reasoning process
encompassing evidence curation and chain-of-thought reasoning for concurrent
textual and visual RAG pipelines. A key novelty of VisDoMRAG is its
consistency-constrained modality fusion mechanism, which aligns the reasoning
processes across modalities at inference time to produce a coherent final
answer. This leads to enhanced accuracy in scenarios where critical information
is distributed across modalities and improved answer verifiability through
implicit context attribution. Through extensive experiments involving
open-source and proprietary large language models, we benchmark
state-of-the-art document QA methods on VisDoMBench. Extensive results show
that VisDoMRAG outperforms unimodal and long-context LLM baselines for
end-to-end multimodal document QA by 12-20%.

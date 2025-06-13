---
layout: publication
title: 'Face The Facts! Evaluating Rag-based Fact-checking Pipelines In Realistic Settings'
authors: Daniel Russo, Stefano Menini, Jacopo Staiano, Marco Guerini
conference: "Arxiv"
year: 2024
bibkey: russo2024face
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15189"}
tags: ['RAG']
---
Natural Language Processing and Generation systems have recently shown the
potential to complement and streamline the costly and time-consuming job of
professional fact-checkers. In this work, we lift several constraints of
current state-of-the-art pipelines for automated fact-checking based on the
Retrieval-Augmented Generation (RAG) paradigm. Our goal is to benchmark, under
more realistic scenarios, RAG-based methods for the generation of verdicts -
i.e., short texts discussing the veracity of a claim - evaluating them on
stylistically complex claims and heterogeneous, yet reliable, knowledge bases.
Our findings show a complex landscape, where, for example, LLM-based retrievers
outperform other retrieval techniques, though they still struggle with
heterogeneous knowledge bases; larger models excel in verdict faithfulness,
while smaller models provide better context adherence, with human evaluations
favouring zero-shot and one-shot approaches for informativeness, and fine-tuned
models for emotional alignment.

---
layout: publication
title: 'Llms Are Not Scorers: Rethinking MT Evaluation With Generation-based Methods'
authors: Hyang Cui
conference: "Arxiv"
year: 2025
bibkey: cui2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16129"}
tags: ['RAG', 'Prompting', 'Applications', 'Reinforcement Learning']
---
Recent studies have applied large language models (LLMs) to machine translation quality estimation (MTQE) by prompting models to assign numeric scores. Nonetheless, these direct scoring methods tend to show low segment-level correlation with human judgments. In this paper, we propose a generation-based evaluation paradigm that leverages decoder-only LLMs to produce high-quality references, followed by semantic similarity scoring using sentence embeddings. We conduct the most extensive evaluation to date in MTQE, covering 8 LLMs and 8 language pairs. Empirical results show that our method outperforms both intra-LLM direct scoring baselines and external non-LLM reference-free metrics from MTME. These findings demonstrate the strength of generation-based evaluation and support a shift toward hybrid approaches that combine fluent generation with accurate semantic assessment.

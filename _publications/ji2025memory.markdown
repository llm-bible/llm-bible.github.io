---
layout: publication
title: 'Memory-aware And Uncertainty-guided Retrieval For Multi-hop Question Answering'
authors: Yuelyu Ji, Rui Meng, Zhuochun Li, Daqing He
conference: "Arxiv"
year: 2025
bibkey: ji2025memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23095"}
tags: ['Tools', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Prompting']
---
Multi-hop question answering (QA) requires models to retrieve and reason over
multiple pieces of evidence. While Retrieval-Augmented Generation (RAG) has
made progress in this area, existing methods often suffer from two key
limitations: (1) fixed or overly frequent retrieval steps, and (2) ineffective
use of previously retrieved knowledge.
  We propose MIND (Memory-Informed and INteractive Dynamic RAG), a framework
that addresses these challenges through: (i) prompt-based entity extraction to
identify reasoning-relevant elements, (ii) dynamic retrieval triggering based
on token-level entropy and attention signals, and (iii) memory-aware filtering,
which stores high-confidence facts across reasoning steps to enable consistent
multi-hop generation.

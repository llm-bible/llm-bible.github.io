---
layout: publication
title: 'LLM Program Optimization Via Retrieval Augmented Search'
authors: Sagnik Anupam, Alexander Shypula, Osbert Bastani
conference: "Arxiv"
year: 2025
bibkey: anupam2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18916'}
tags: ['Interpretability and Explainability', 'Efficiency and Optimization', 'Training Techniques']
---
With the advent of large language models (LLMs), there has been a great deal
of interest in applying them to solve difficult programming tasks. Recent work
has demonstrated their potential at program optimization, a key challenge in
programming languages research. We propose a blackbox adaptation method called
Retrieval Augmented Search (RAS) that performs beam search over candidate
optimizations; at each step, it retrieves in-context examples from a given
training dataset of slow-fast program pairs to guide the LLM. Critically, we
find that performing contextual retrieval based on an LLM-generated natural
language description significantly outperforms retrieval based on the source
code. In addition, we propose a method called AEGIS for improving
interpretability by decomposing training examples into "atomic edits" that are
significantly more incremental in nature. We show that RAS performs 1.8\\(\times\\)
better than prior state-of-the-art blackbox adaptation strategies, and that
AEGIS performs 1.37\\(\times\\) better while performing significantly smaller
edits.

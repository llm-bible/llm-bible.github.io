---
layout: publication
title: 'Walking Down The Memory Maze: Beyond Context Limit Through Interactive Reading'
authors: Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz
conference: "Arxiv"
year: 2023
bibkey: chen2023walking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05029"}
tags: ['Agentic', 'Model Architecture', 'Interpretability', 'Transformer', 'Interpretability and Explainability', 'Prompting', 'Applications', 'Attention Mechanism']
---
Large language models (LLMs) have advanced in large strides due to the
effectiveness of the self-attention mechanism that processes and compares all
tokens at once. However, this mechanism comes with a fundamental issue -- the
predetermined context window is bound to be limited. Despite attempts to extend
the context window through methods like extrapolating the positional embedding,
using recurrence, or selectively retrieving essential parts of the long
sequence, long-text understanding continues to be a challenge. We propose an
alternative approach which instead treats the LLM as an interactive agent,
allowing it to decide how to read the text via iterative prompting. We
introduce MemWalker, a method that first processes the long context into a tree
of summary nodes. Upon receiving a query, the model navigates this tree in
search of relevant information, and responds once it gathers sufficient
information. On long-text question answering tasks our method outperforms
baseline approaches that use long context windows, recurrence, and retrieval.
We show that, beyond effective reading, MemWalker enhances explainability by
highlighting the reasoning steps as it interactively reads the text;
pinpointing the relevant text segments related to the query.

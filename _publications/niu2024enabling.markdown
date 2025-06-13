---
layout: publication
title: 'ATP: Enabling Fast LLM Serving Via Attention On Top Principal Keys'
authors: Yue Niu, Saurav Prakash, Salman Avestimehr
conference: "Arxiv"
year: 2024
bibkey: niu2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02352"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'BERT']
---
We propose a new attention mechanism with linear complexity, ATP, that
fixates \textbf\{A\}ttention on \textbf\{T\}op \textbf\{P\}rincipal keys, rather than
on each individual token. Particularly, ATP is driven by an important
observation that input sequences are typically low-rank, i.e., input sequences
can be represented by a few principal bases. Therefore, instead of directly
iterating over all the input tokens, ATP transforms inputs into an orthogonal
space and computes attention only on the top principal bases (keys). Owing to
the observed low-rank structure in input sequences, ATP is able to capture
semantic relationships in input sequences with a few principal keys.
Furthermore, the attention complexity is reduced from *quadratic* to
*linear* without incurring a noticeable performance drop. ATP further
reduces complexity for other linear layers with low-rank inputs, leading to
more speedup compared to prior works that solely target the attention module.
Our evaluations on various models (e.g., BERT and Llama) demonstrate that ATP
achieves comparable accuracy with much lower computation and memory complexity
than the standard attention mechanism. In particular, ATP barely loses accuracy
with only \\(1/2\\) principal keys, and only incurs around \\(2%\\) accuracy drops
with \\(1/4\\) principal keys.

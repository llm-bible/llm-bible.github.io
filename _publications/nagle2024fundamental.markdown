---
layout: publication
title: 'Fundamental Limits Of Prompt Compression: A Rate-distortion Framework For Black-box Language Models'
authors: Alliot Nagle, Adway Girish, Marco Bondaschi, Michael Gastpar, Ashok Vardhan Makkuva, Hyeji Kim
conference: "Arxiv"
year: 2024
bibkey: nagle2024fundamental
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15504"}
tags: ['Prompting', 'Tools']
---
We formalize the problem of prompt compression for large language models
(LLMs) and present a framework to unify token-level prompt compression methods
which create hard prompts for black-box models. We derive the distortion-rate
function for this setup as a linear program, and provide an efficient algorithm
to compute this fundamental limit via the dual of the linear program. Using the
distortion-rate function as the baseline, we study the performance of existing
compression schemes on a synthetic dataset consisting of prompts generated from
a Markov chain, natural language queries, and their respective answers. Our
empirical analysis demonstrates the criticality of query-aware prompt
compression, where the compressor has knowledge of the downstream task/query
for the black-box LLM. We show that there is a large gap between the
performance of current prompt compression methods and the optimal strategy, and
propose Adaptive QuerySelect, a query-aware, variable-rate adaptation of a
prior work to close the gap. We extend our experiments to a small natural
language dataset to further confirm our findings on our synthetic dataset.

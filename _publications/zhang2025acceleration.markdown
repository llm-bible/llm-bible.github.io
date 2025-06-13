---
layout: publication
title: 'Acceleration Multiple Heads Decoding For LLM Via Dynamic Tree Attention'
authors: Zhendong Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025acceleration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05947"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism']
---
Multiple heads decoding accelerates the inference of Large Language Models
(LLMs) by predicting next several tokens simultaneously. It generates and
verifies multiple candidate sequences in parallel via tree attention with a
fixed structure. In this paper, we replace the fixed tree attention with
dynamic tree attention on multiple head decoding, specifically in the context
of MEDUSA. We propose a simple and low complexity strategy to generate
candidates and construct the dynamic tree structure. Preliminary experiments
show that the proposed method improves the decoding efficiency of multiple head
decoding for LLMs while maintaining the generation quality. This result
demonstrates the potential for improvement of multiple head decoding in
candidate generation.

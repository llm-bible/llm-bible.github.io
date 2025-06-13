---
layout: publication
title: 'Why And How Llms Hallucinate: Connecting The Dots With Subsequence Associations'
authors: Yiyou Sun, Yu Gai, Lijie Chen, Abhilasha Ravichander, Yejin Choi, Dawn Song
conference: "Arxiv"
year: 2025
bibkey: sun2025why
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12691'}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) frequently generate hallucinations-content that
deviates from factual accuracy or provided context-posing challenges for
diagnosis due to the complex interplay of underlying causes. This paper
introduces a subsequence association framework to systematically trace and
understand hallucinations. Our key insight is that hallucinations arise when
dominant hallucinatory associations outweigh faithful ones. Through theoretical
and empirical analyses, we demonstrate that decoder-only transformers
effectively function as subsequence embedding models, with linear layers
encoding input-output associations. We propose a tracing algorithm that
identifies causal subsequences by analyzing hallucination probabilities across
randomized input contexts. Experiments show our method outperforms standard
attribution techniques in identifying hallucination causes and aligns with
evidence from the model's training corpus. This work provides a unified
perspective on hallucinations and a robust framework for their tracing and
analysis.

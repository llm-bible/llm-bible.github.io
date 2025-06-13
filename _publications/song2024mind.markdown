---
layout: publication
title: 'Mind The Gap: Examining The Self-improvement Capabilities Of Large Language Models'
authors: Yuda Song, Hanlin Zhang, Carson Eisenach, Sham Kakade, Dean Foster, Udaya Ghai
conference: "Arxiv"
year: 2024
bibkey: song2024mind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02674"}
tags: ['Training Techniques', 'Pre-Training', 'Tools']
---
Self-improvement is a mechanism in Large Language Model (LLM) pre-training,
post-training and test-time inference. We explore a framework where the model
verifies its own outputs, filters or reweights data based on this verification,
and distills the filtered data. Despite several empirical successes, a
fundamental understanding is still lacking. In this work, we initiate a
comprehensive, modular and controlled study on LLM self-improvement. We provide
a mathematical formulation for self-improvement, which is largely governed by a
quantity which we formalize as the generation-verification gap. Through
experiments with various model families and tasks, we discover a scaling
phenomenon of self-improvement -- a variant of the generation-verification gap
scales monotonically with the model pre-training flops. We also examine when
self-improvement is possible, an iterative self-improvement procedure, and ways
to improve its performance. Our findings not only advance understanding of LLM
self-improvement with practical implications, but also open numerous avenues
for future research into its capabilities and boundaries.

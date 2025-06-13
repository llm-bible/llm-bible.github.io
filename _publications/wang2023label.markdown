---
layout: publication
title: 'Label Words Are Anchors: An Information Flow Perspective For Understanding In-context Learning'
authors: Lean Wang, Lei Li, Damai Dai, Deli Chen, Hao Zhou, Fandong Meng, Jie Zhou, Xu Sun
conference: "Arxiv"
year: 2023
bibkey: wang2023label
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.14160'}
tags: ['GPT', 'Tools', 'Applications', 'Prompting', 'Model Architecture', 'Reinforcement Learning', 'In-Context Learning']
---
In-context learning (ICL) emerges as a promising capability of large language
models (LLMs) by providing them with demonstration examples to perform diverse
tasks. However, the underlying mechanism of how LLMs learn from the provided
context remains under-explored. In this paper, we investigate the working
mechanism of ICL through an information flow lens. Our findings reveal that
label words in the demonstration examples function as anchors: (1) semantic
information aggregates into label word representations during the shallow
computation layers' processing; (2) the consolidated information in label words
serves as a reference for LLMs' final predictions. Based on these insights, we
introduce an anchor re-weighting method to improve ICL performance, a
demonstration compression technique to expedite inference, and an analysis
framework for diagnosing ICL errors in GPT2-XL. The promising applications of
our findings again validate the uncovered ICL working mechanism and pave the
way for future studies.

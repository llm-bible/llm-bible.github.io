---
layout: publication
title: 'Think More, Hallucinate Less: Mitigating Hallucinations Via Dual Process Of Fast And Slow Thinking'
authors: Xiaoxue Cheng, Junyi Li, Wayne Xin Zhao, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: cheng2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01306"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Language Modeling', 'Reinforcement Learning']
---
Large language models (LLMs) demonstrate exceptional capabilities, yet still
face the hallucination issue. Typical text generation approaches adopt an
auto-regressive generation without deliberate reasoning, which often results in
untrustworthy and factually inaccurate responses. In this paper, we propose
HaluSearch, a novel framework that incorporates tree search-based algorithms
(e.g. MCTS) to enable an explicit slow thinking generation process for
mitigating hallucinations of LLMs during inference. Specifically, HaluSearch
frames text generation as a step-by-step reasoning process, using a
self-evaluation reward model to score each generation step and guide the tree
search towards the most reliable generation pathway for fully exploiting the
internal knowledge of LLMs. To balance efficiency and quality, we introduce a
hierarchical thinking system switch mechanism inspired by the dual process
theory in cognitive science, which dynamically alternates between fast and slow
thinking modes at both the instance and step levels, adapting to the complexity
of questions and reasoning states. We conduct extensive experiments on both
English and Chinese datasets and the results show that our approach
significantly outperforms baseline approaches.

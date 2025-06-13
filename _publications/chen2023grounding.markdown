---
layout: publication
title: 'Grounding-prompter: Prompting LLM With Multimodal Information For Temporal Sentence Grounding In Long Videos'
authors: Houlun Chen, Xin Wang, Hong Chen, Zihan Song, Jia Jia, Wenwu Zhu
conference: "Arxiv"
year: 2023
bibkey: chen2023grounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17117"}
tags: ['Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models', 'Prompting']
---
Temporal Sentence Grounding (TSG), which aims to localize moments from videos
based on the given natural language queries, has attracted widespread
attention. Existing works are mainly designed for short videos, failing to
handle TSG in long videos, which poses two challenges: i) complicated contexts
in long videos require temporal reasoning over longer moment sequences, and ii)
multiple modalities including textual speech with rich information require
special designs for content understanding in long videos. To tackle these
challenges, in this work we propose a Grounding-Prompter method, which is
capable of conducting TSG in long videos through prompting LLM with multimodal
information. In detail, we first transform the TSG task and its multimodal
inputs including speech and visual, into compressed task textualization.
Furthermore, to enhance temporal reasoning under complicated contexts, a
Boundary-Perceptive Prompting strategy is proposed, which contains three folds:
i) we design a novel Multiscale Denoising Chain-of-Thought (CoT) to combine
global and local semantics with noise filtering step by step, ii) we set up
validity principles capable of constraining LLM to generate reasonable
predictions following specific formats, and iii) we introduce one-shot
In-Context-Learning (ICL) to boost reasoning through imitation, enhancing LLM
in TSG task understanding. Experiments demonstrate the state-of-the-art
performance of our Grounding-Prompter method, revealing the benefits of
prompting LLM with multimodal information for TSG in long videos.

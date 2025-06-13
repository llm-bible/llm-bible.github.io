---
layout: publication
title: 'POSS: Position Specialist Generates Better Draft For Speculative Decoding'
authors: Langlin Huang, Chengsong Huang, Jixuan Leng, Di Huang, Jiaxin Huang
conference: "Arxiv"
year: 2025
bibkey: huang2025position
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03566'}
  - {name: "Code", url: 'https://github.com/shrango/PosS'}
tags: ['RAG', 'Has Code']
---
Speculative decoding accelerates Large Language Model (LLM) inference by using a small draft model to predict multiple tokens, and a large target model to verify these tokens in parallel. Recent studies leverage the hidden state of the target model to enhance draft model prediction accuracy. However, existing methods suffer from the degrading quality of draft token predictions at later positions, due to error accumulation in draft model generated features. In this paper, we propose Position Specialists (PosS), which consist of multiple position-specialized draft layers to generate tokens at assigned position(s). Position specialists greatly improve token acceptance rate at later positions per drafting round, as each specialist only needs to focus on handling a certain level of draft model feature deviation. Experiment results on Llama-3-8B-Instruct and Llama-2-13B-chat across six datasets demonstrate that PosS effectively improves over baselines on average acceptance length and speed-up ratio. Our codebase is available at https://github.com/shrango/PosS.

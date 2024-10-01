---
layout: publication
title: 'Amr-to-text Generation With Cache Transition Systems'
authors: Jin Lisa, Gildea Daniel
conference: "Arxiv"
year: 2019
bibkey: jin2019amr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1912.01682"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning']
---
"Text generation from AMR involves emitting sentences that reflect the meaning of their AMR annotations. Neural sequence-to-sequence models have successfully been used to decode strings from flattened graphs (e.g., using depth-first or random traversal). Such models often rely on attention-based decoders to map AMR node to English token sequences. Instead of linearizing AMR, we directly encode its graph structure and delegate traversal to the decoder. To enforce a sentence-aligned graph traversal and provide local graph context, we predict transition-based parser actions in addition to English words. We present two model variants: one generates parser actions prior to words, while the other interleaves actions with words."

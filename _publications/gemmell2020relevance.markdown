---
layout: publication
title: 'Relevance Transformer: Generating Concise Code Snippets With Relevance Feedback'
authors: Gemmell Carlos, Rossetto Federico, Dalton Jeffrey
conference: "Arxiv"
year: 2020
bibkey: gemmell2020relevance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.02609"}
tags: ['Applications', 'Ethics And Bias', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Tools capable of automatic code generation have the potential to augment
programmer's capabilities. While straightforward code retrieval is incorporated
into many IDEs, an emerging area is explicit code generation. Code generation
is currently approached as a Machine Translation task, with Recurrent Neural
Network (RNN) based encoder-decoder architectures trained on code-description
pairs. In this work we introduce and study modern Transformer architectures for
this task. We further propose a new model called the Relevance Transformer that
incorporates external knowledge using pseudo-relevance feedback. The Relevance
Transformer biases the decoding process to be similar to existing retrieved
code while enforcing diversity. We perform experiments on multiple standard
benchmark datasets for code generation including Django, Hearthstone, and
CoNaLa. The results show improvements over state-of-the-art methods based on
BLEU evaluation. The Relevance Transformer model shows the potential of
Transformer-based architectures for code generation and introduces a method of
incorporating pseudo-relevance feedback during inference.
